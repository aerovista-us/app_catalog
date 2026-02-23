AeroVista App Catalog (v3)

Includes:
- Catalog view (search/filter/sort)
- Duplicate controls
- "Only Active" filter (based on NXCore runtime snapshot)
- NXCore Runtime tab:
  - Services -> ports -> compose files
  - Compose stacks and their compose.yml paths
  - Host-level services

Run locally:
1) In the parent folder of this directory, run:
   python -m http.server 8080
2) Open:
   http://localhost:8080/app_catalog_v3/index.html

Deploy:
- Put this folder on your external SSD
- Serve with nginx container (recommended) or Traefik route.
