<<<<<<< HEAD

```
code-2-6
├─ data-main
│  ├─ data.md
│  ├─ fastapis
│  │  ├─ alembic.ini
│  │  ├─ app
│  │  │  ├─ core
│  │  │  │  ├─ config.py
│  │  │  │  ├─ error.py
│  │  │  │  ├─ local.env
│  │  │  │  ├─ mongo.py
│  │  │  │  ├─ mysql.py
│  │  │  │  ├─ security.py
│  │  │  │  ├─ upload.py
│  │  │  │  └─ __pycache__
│  │  │  │     ├─ config.cpython-313.pyc
│  │  │  │     ├─ error.cpython-313.pyc
│  │  │  │     ├─ mongo.cpython-313.pyc
│  │  │  │     ├─ mysql.cpython-313.pyc
│  │  │  │     ├─ security.cpython-313.pyc
│  │  │  │     └─ upload.cpython-313.pyc
│  │  │  ├─ entity
│  │  │  │  ├─ company.py
│  │  │  │  ├─ equipement_fuel.py
│  │  │  │  ├─ equipment.py
│  │  │  │  ├─ meta.py
│  │  │  │  ├─ README.md
│  │  │  │  ├─ user.py
│  │  │  │  ├─ vessel.py
│  │  │  │  ├─ vessel_data_upload.py
│  │  │  │  └─ __pycache__
│  │  │  │     ├─ company.cpython-313.pyc
│  │  │  │     ├─ equipement_fuel.cpython-313.pyc
│  │  │  │     ├─ equipment.cpython-313.pyc
│  │  │  │     ├─ meta.cpython-313.pyc
│  │  │  │     ├─ user.cpython-313.pyc
│  │  │  │     ├─ vessel.cpython-313.pyc
│  │  │  │     └─ vessel_data_upload.cpython-313.pyc
│  │  │  ├─ main.py
│  │  │  ├─ model
│  │  │  │  ├─ company.py
│  │  │  │  ├─ equipment.py
│  │  │  │  ├─ power_speed_curve.py
│  │  │  │  ├─ response.py
│  │  │  │  ├─ user.py
│  │  │  │  ├─ vessel.py
│  │  │  │  ├─ vessel_data_upload.py
│  │  │  │  ├─ __init__.py
│  │  │  │  └─ __pycache__
│  │  │  │     ├─ company.cpython-313.pyc
│  │  │  │     ├─ equipment.cpython-313.pyc
│  │  │  │     ├─ response.cpython-313.pyc
│  │  │  │     ├─ user.cpython-313.pyc
│  │  │  │     ├─ vessel.cpython-313.pyc
│  │  │  │     ├─ vessel_data_upload.cpython-313.pyc
│  │  │  │     └─ __init__.cpython-313.pyc
│  │  │  ├─ router
│  │  │  │  ├─ company.py
│  │  │  │  ├─ equipment.py
│  │  │  │  ├─ meta.py
│  │  │  │  ├─ upload.py
│  │  │  │  ├─ user.py
│  │  │  │  ├─ vessel.py
│  │  │  │  ├─ vessel_route.py
│  │  │  │  ├─ __init__.py
│  │  │  │  └─ __pycache__
│  │  │  │     ├─ company.cpython-313.pyc
│  │  │  │     ├─ meta.cpython-313.pyc
│  │  │  │     ├─ upload.cpython-313.pyc
│  │  │  │     ├─ user.cpython-313.pyc
│  │  │  │     ├─ vessel.cpython-313.pyc
│  │  │  │     ├─ vessel_route.cpython-313.pyc
│  │  │  │     └─ __init__.cpython-313.pyc
│  │  │  ├─ scripts
│  │  │  │  ├─ DDL
│  │  │  │  │  ├─ company.sql
│  │  │  │  │  ├─ equipement.sql
│  │  │  │  │  ├─ equipment_fuel.sql
│  │  │  │  │  ├─ meta.sql
│  │  │  │  │  ├─ user.sql
│  │  │  │  │  └─ vessel.sql
│  │  │  │  └─ DML
│  │  │  │     └─ dml.sql
│  │  │  ├─ service
│  │  │  │  ├─ company.py
│  │  │  │  ├─ data.py
│  │  │  │  ├─ equipment.py
│  │  │  │  ├─ meta.py
│  │  │  │  ├─ upload.py
│  │  │  │  ├─ user.py
│  │  │  │  ├─ vessel.py
│  │  │  │  ├─ __init__.py
│  │  │  │  └─ __pycache__
│  │  │  │     ├─ company.cpython-313.pyc
│  │  │  │     ├─ data.cpython-313.pyc
│  │  │  │     ├─ meta.cpython-313.pyc
│  │  │  │     ├─ upload.cpython-313.pyc
│  │  │  │     ├─ user.cpython-313.pyc
│  │  │  │     ├─ vessel.cpython-313.pyc
│  │  │  │     └─ __init__.cpython-313.pyc
│  │  │  ├─ __init__.py
│  │  │  └─ __pycache__
│  │  │     ├─ main.cpython-313.pyc
│  │  │     └─ __init__.cpython-313.pyc
│  │  ├─ app.log
│  │  ├─ compose.yml
│  │  ├─ Dockerfile
│  │  ├─ local.env
│  │  ├─ migration
│  │  │  ├─ env.py
│  │  │  ├─ README.md
│  │  │  ├─ script.py.mako
│  │  │  └─ versions
│  │  │     ├─ 001_create_meta_data.py
│  │  │     ├─ 002_insert_meta_data.py
│  │  │     ├─ 003_create_company_table.py
│  │  │     ├─ 004_create_user_table.py
│  │  │     ├─ 005_create_vessel_table.py
│  │  │     ├─ 006_create_equipment_table.py
│  │  │     ├─ 007_create_equipment_fueltype_mapping_table.py
│  │  │     └─ 008_create_data_upload_table.py
│  │  ├─ poetry.lock
│  │  ├─ pyproject.toml
│  │  ├─ pytest-coverage.txt
│  │  ├─ pytest.xml
│  │  ├─ README.md
│  │  ├─ requirements.txt
│  │  └─ tests
│  │     ├─ conftest.py
│  │     ├─ test_company_crud.py
│  │     ├─ test_meta_r.py
│  │     ├─ test_upload_cr.py
│  │     ├─ test_user_crud.py
│  │     ├─ test_vessel_crud.py
│  │     ├─ __init__.py
│  │     └─ __pycache__
│  │        ├─ conftest.cpython-313-pytest-8.3.4.pyc
│  │        └─ __init__.cpython-313.pyc
│  ├─ Jenkinsfile
│  ├─ layer.md
│  ├─ playground
│  │  ├─ 1-to-m.py
│  │  ├─ login
│  │  │  ├─ 1.py
│  │  │  ├─ 2.py
│  │  │  ├─ 3.py
│  │  │  ├─ 4.py
│  │  │  ├─ 5.py
│  │  │  └─ __pycache__
│  │  │     └─ 5.cpython-313.pyc
│  │  └─ test.db
│  ├─ README.md
│  └─ REST.md
├─ functional-module
│  ├─ clean.py
│  └─ fleet_route_analysis.py
├─ next
│  └─ login-app
│     ├─ app
│     │  ├─ favicon.ico
│     │  ├─ globals.css
│     │  ├─ layout.tsx
│     │  └─ page.tsx
│     ├─ eslint.config.mjs
│     ├─ next-env.d.ts
│     ├─ next.config.ts
│     ├─ package-lock.json
│     ├─ package.json
│     ├─ postcss.config.mjs
│     ├─ public
│     │  ├─ file.svg
│     │  ├─ globe.svg
│     │  ├─ next.svg
│     │  ├─ vercel.svg
│     │  └─ window.svg
│     ├─ README.md
│     ├─ tailwind.config.ts
│     └─ tsconfig.json
├─ README.md
└─ vessel-system-frontend
   ├─ .env.local
   ├─ .next
   │  ├─ app-build-manifest.json
   │  ├─ build
   │  │  └─ chunks
   │  │     ├─ postcss_config_mjs_transform_ts_89c7e7._.js
   │  │     ├─ postcss_config_mjs_transform_ts_89c7e7._.js.map
   │  │     ├─ [root of the server]__05f88b._.js
   │  │     ├─ [root of the server]__05f88b._.js.map
   │  │     ├─ [root of the server]__fd836e._.js
   │  │     ├─ [root of the server]__fd836e._.js.map
   │  │     ├─ [turbopack]_runtime.js
   │  │     └─ [turbopack]_runtime.js.map
   │  ├─ build-manifest.json
   │  ├─ cache
   │  │  └─ .rscinfo
   │  ├─ fallback-build-manifest.json
   │  ├─ package.json
   │  ├─ react-loadable-manifest.json
   │  ├─ server
   │  │  ├─ app
   │  │  │  ├─ dashboard
   │  │  │  │  ├─ data-analysis
   │  │  │  │  │  ├─ page
   │  │  │  │  │  │  ├─ app-build-manifest.json
   │  │  │  │  │  │  ├─ app-paths-manifest.json
   │  │  │  │  │  │  ├─ build-manifest.json
   │  │  │  │  │  │  ├─ next-font-manifest.json
   │  │  │  │  │  │  ├─ react-loadable-manifest.json
   │  │  │  │  │  │  └─ server-reference-manifest.json
   │  │  │  │  │  ├─ page.js
   │  │  │  │  │  ├─ page.js.map
   │  │  │  │  │  └─ page_client-reference-manifest.js
   │  │  │  │  ├─ data-upload
   │  │  │  │  │  ├─ page
   │  │  │  │  │  │  ├─ app-build-manifest.json
   │  │  │  │  │  │  ├─ app-paths-manifest.json
   │  │  │  │  │  │  ├─ build-manifest.json
   │  │  │  │  │  │  ├─ next-font-manifest.json
   │  │  │  │  │  │  ├─ react-loadable-manifest.json
   │  │  │  │  │  │  └─ server-reference-manifest.json
   │  │  │  │  │  ├─ page.js
   │  │  │  │  │  ├─ page.js.map
   │  │  │  │  │  └─ page_client-reference-manifest.js
   │  │  │  │  ├─ feedback
   │  │  │  │  │  ├─ page
   │  │  │  │  │  │  ├─ app-build-manifest.json
   │  │  │  │  │  │  ├─ app-paths-manifest.json
   │  │  │  │  │  │  ├─ build-manifest.json
   │  │  │  │  │  │  ├─ next-font-manifest.json
   │  │  │  │  │  │  ├─ react-loadable-manifest.json
   │  │  │  │  │  │  └─ server-reference-manifest.json
   │  │  │  │  │  ├─ page.js
   │  │  │  │  │  ├─ page.js.map
   │  │  │  │  │  └─ page_client-reference-manifest.js
   │  │  │  │  ├─ page
   │  │  │  │  │  ├─ app-build-manifest.json
   │  │  │  │  │  ├─ app-paths-manifest.json
   │  │  │  │  │  ├─ build-manifest.json
   │  │  │  │  │  ├─ next-font-manifest.json
   │  │  │  │  │  ├─ react-loadable-manifest.json
   │  │  │  │  │  └─ server-reference-manifest.json
   │  │  │  │  ├─ page.js
   │  │  │  │  ├─ page.js.map
   │  │  │  │  ├─ page_client-reference-manifest.js
   │  │  │  │  ├─ users
   │  │  │  │  │  ├─ page
   │  │  │  │  │  │  ├─ app-build-manifest.json
   │  │  │  │  │  │  ├─ app-paths-manifest.json
   │  │  │  │  │  │  ├─ build-manifest.json
   │  │  │  │  │  │  ├─ next-font-manifest.json
   │  │  │  │  │  │  ├─ react-loadable-manifest.json
   │  │  │  │  │  │  └─ server-reference-manifest.json
   │  │  │  │  │  ├─ page.js
   │  │  │  │  │  ├─ page.js.map
   │  │  │  │  │  └─ page_client-reference-manifest.js
   │  │  │  │  └─ vessel-status
   │  │  │  │     ├─ page
   │  │  │  │     │  ├─ app-build-manifest.json
   │  │  │  │     │  ├─ app-paths-manifest.json
   │  │  │  │     │  ├─ build-manifest.json
   │  │  │  │     │  ├─ next-font-manifest.json
   │  │  │  │     │  ├─ react-loadable-manifest.json
   │  │  │  │     │  └─ server-reference-manifest.json
   │  │  │  │     ├─ page.js
   │  │  │  │     ├─ page.js.map
   │  │  │  │     └─ page_client-reference-manifest.js
   │  │  │  ├─ favicon.ico
   │  │  │  │  ├─ route
   │  │  │  │  │  ├─ app-paths-manifest.json
   │  │  │  │  │  ├─ next-font-manifest.json
   │  │  │  │  │  └─ react-loadable-manifest.json
   │  │  │  │  ├─ route.js
   │  │  │  │  └─ route.js.map
   │  │  │  ├─ login
   │  │  │  │  ├─ page
   │  │  │  │  │  ├─ app-build-manifest.json
   │  │  │  │  │  ├─ app-paths-manifest.json
   │  │  │  │  │  ├─ build-manifest.json
   │  │  │  │  │  ├─ next-font-manifest.json
   │  │  │  │  │  ├─ react-loadable-manifest.json
   │  │  │  │  │  └─ server-reference-manifest.json
   │  │  │  │  ├─ page.js
   │  │  │  │  ├─ page.js.map
   │  │  │  │  └─ page_client-reference-manifest.js
   │  │  │  ├─ map
   │  │  │  │  ├─ page
   │  │  │  │  │  ├─ app-build-manifest.json
   │  │  │  │  │  ├─ app-paths-manifest.json
   │  │  │  │  │  ├─ build-manifest.json
   │  │  │  │  │  ├─ next-font-manifest.json
   │  │  │  │  │  ├─ react-loadable-manifest.json
   │  │  │  │  │  └─ server-reference-manifest.json
   │  │  │  │  ├─ page.js
   │  │  │  │  ├─ page.js.map
   │  │  │  │  └─ page_client-reference-manifest.js
   │  │  │  ├─ page
   │  │  │  │  ├─ app-build-manifest.json
   │  │  │  │  ├─ app-paths-manifest.json
   │  │  │  │  ├─ build-manifest.json
   │  │  │  │  ├─ next-font-manifest.json
   │  │  │  │  ├─ react-loadable-manifest.json
   │  │  │  │  └─ server-reference-manifest.json
   │  │  │  ├─ page.js
   │  │  │  ├─ page.js.map
   │  │  │  ├─ page_client-reference-manifest.js
   │  │  │  ├─ user
   │  │  │  │  ├─ page
   │  │  │  │  │  ├─ app-build-manifest.json
   │  │  │  │  │  ├─ app-paths-manifest.json
   │  │  │  │  │  ├─ build-manifest.json
   │  │  │  │  │  ├─ next-font-manifest.json
   │  │  │  │  │  ├─ react-loadable-manifest.json
   │  │  │  │  │  └─ server-reference-manifest.json
   │  │  │  │  ├─ page.js
   │  │  │  │  ├─ page.js.map
   │  │  │  │  └─ page_client-reference-manifest.js
   │  │  │  └─ _not-found
   │  │  │     ├─ page
   │  │  │     │  ├─ app-build-manifest.json
   │  │  │     │  ├─ app-paths-manifest.json
   │  │  │     │  ├─ build-manifest.json
   │  │  │     │  ├─ next-font-manifest.json
   │  │  │     │  ├─ react-loadable-manifest.json
   │  │  │     │  └─ server-reference-manifest.json
   │  │  │     ├─ page.js
   │  │  │     ├─ page.js.map
   │  │  │     └─ page_client-reference-manifest.js
   │  │  ├─ app-paths-manifest.json
   │  │  ├─ chunks
   │  │  │  ├─ ssr
   │  │  │  │  ├─ app_dashboard_layout_tsx_565466._.js
   │  │  │  │  ├─ app_dashboard_layout_tsx_565466._.js.map
   │  │  │  │  ├─ app_dashboard_layout_tsx_9efbc5._.js
   │  │  │  │  ├─ app_dashboard_layout_tsx_9efbc5._.js.map
   │  │  │  │  ├─ app_dashboard_layout_tsx_b0e10b._.js
   │  │  │  │  ├─ app_dashboard_layout_tsx_b0e10b._.js.map
   │  │  │  │  ├─ app_db13a2._.js
   │  │  │  │  ├─ app_db13a2._.js.map
   │  │  │  │  ├─ app_globals_73c377.css
   │  │  │  │  ├─ app_globals_73c377.css.map
   │  │  │  │  ├─ app_globals_b52d8e.css
   │  │  │  │  ├─ app_globals_b52d8e.css.map
   │  │  │  │  ├─ app_layout_tsx_ab3da7._.js
   │  │  │  │  ├─ app_layout_tsx_ab3da7._.js.map
   │  │  │  │  ├─ app_login_layout_tsx_76e512._.js
   │  │  │  │  ├─ app_login_layout_tsx_76e512._.js.map
   │  │  │  │  ├─ app_map_layout_tsx_7d29fc._.js
   │  │  │  │  ├─ app_map_layout_tsx_7d29fc._.js.map
   │  │  │  │  ├─ app_map_layout_tsx_cbf1ea._.js
   │  │  │  │  ├─ app_map_layout_tsx_cbf1ea._.js.map
   │  │  │  │  ├─ app_map_layout_tsx_d2ad01._.js
   │  │  │  │  ├─ app_map_layout_tsx_d2ad01._.js.map
   │  │  │  │  ├─ app_page_tsx_41f218._.js
   │  │  │  │  ├─ app_page_tsx_41f218._.js.map
   │  │  │  │  ├─ [next]_internal_font_google_55dcbe._.css
   │  │  │  │  ├─ [next]_internal_font_google_55dcbe._.css.map
   │  │  │  │  ├─ [next]_internal_font_google_geist_e531dabc_module_b52d8e.css
   │  │  │  │  ├─ [next]_internal_font_google_geist_e531dabc_module_b52d8e.css.map
   │  │  │  │  ├─ [next]_internal_font_google_geist_mono_68a01160_module_b52d8e.css
   │  │  │  │  ├─ [next]_internal_font_google_geist_mono_68a01160_module_b52d8e.css.map
   │  │  │  │  ├─ [root of the server]__054733._.js
   │  │  │  │  ├─ [root of the server]__054733._.js.map
   │  │  │  │  ├─ [root of the server]__08831c._.js
   │  │  │  │  ├─ [root of the server]__08831c._.js.map
   │  │  │  │  ├─ [root of the server]__14e134._.js
   │  │  │  │  ├─ [root of the server]__14e134._.js.map
   │  │  │  │  ├─ [root of the server]__17874e._.js
   │  │  │  │  ├─ [root of the server]__17874e._.js.map
   │  │  │  │  ├─ [root of the server]__19b76f._.js
   │  │  │  │  ├─ [root of the server]__19b76f._.js.map
   │  │  │  │  ├─ [root of the server]__281bd3._.js
   │  │  │  │  ├─ [root of the server]__281bd3._.js.map
   │  │  │  │  ├─ [root of the server]__2db7c3._.js
   │  │  │  │  ├─ [root of the server]__2db7c3._.js.map
   │  │  │  │  ├─ [root of the server]__3d9cc1._.js
   │  │  │  │  ├─ [root of the server]__3d9cc1._.js.map
   │  │  │  │  ├─ [root of the server]__3ddedf._.js
   │  │  │  │  ├─ [root of the server]__3ddedf._.js.map
   │  │  │  │  ├─ [root of the server]__41e732._.js
   │  │  │  │  ├─ [root of the server]__41e732._.js.map
   │  │  │  │  ├─ [root of the server]__44a181._.js
   │  │  │  │  ├─ [root of the server]__44a181._.js.map
   │  │  │  │  ├─ [root of the server]__45393c._.js
   │  │  │  │  ├─ [root of the server]__45393c._.js.map
   │  │  │  │  ├─ [root of the server]__592060._.js
   │  │  │  │  ├─ [root of the server]__592060._.js.map
   │  │  │  │  ├─ [root of the server]__5c8cf4._.js
   │  │  │  │  ├─ [root of the server]__5c8cf4._.js.map
   │  │  │  │  ├─ [root of the server]__67f645._.js
   │  │  │  │  ├─ [root of the server]__67f645._.js.map
   │  │  │  │  ├─ [root of the server]__688d87._.js
   │  │  │  │  ├─ [root of the server]__688d87._.js.map
   │  │  │  │  ├─ [root of the server]__6fb00f._.js
   │  │  │  │  ├─ [root of the server]__6fb00f._.js.map
   │  │  │  │  ├─ [root of the server]__716e43._.js
   │  │  │  │  ├─ [root of the server]__716e43._.js.map
   │  │  │  │  ├─ [root of the server]__768201._.js
   │  │  │  │  ├─ [root of the server]__768201._.js.map
   │  │  │  │  ├─ [root of the server]__7fa8a8._.js
   │  │  │  │  ├─ [root of the server]__7fa8a8._.js.map
   │  │  │  │  ├─ [root of the server]__80d841._.js
   │  │  │  │  ├─ [root of the server]__80d841._.js.map
   │  │  │  │  ├─ [root of the server]__86e789._.js
   │  │  │  │  ├─ [root of the server]__86e789._.js.map
   │  │  │  │  ├─ [root of the server]__977b1a._.js
   │  │  │  │  ├─ [root of the server]__977b1a._.js.map
   │  │  │  │  ├─ [root of the server]__9d1267._.css
   │  │  │  │  ├─ [root of the server]__9d1267._.css.map
   │  │  │  │  ├─ [root of the server]__be4c30._.js
   │  │  │  │  ├─ [root of the server]__be4c30._.js.map
   │  │  │  │  ├─ [root of the server]__c3f22f._.js
   │  │  │  │  ├─ [root of the server]__c3f22f._.js.map
   │  │  │  │  ├─ [root of the server]__ca6de5._.js
   │  │  │  │  ├─ [root of the server]__ca6de5._.js.map
   │  │  │  │  ├─ [root of the server]__cc9751._.js
   │  │  │  │  ├─ [root of the server]__cc9751._.js.map
   │  │  │  │  ├─ [root of the server]__d3700a._.js
   │  │  │  │  ├─ [root of the server]__d3700a._.js.map
   │  │  │  │  ├─ [root of the server]__d4a2ae._.js
   │  │  │  │  ├─ [root of the server]__d4a2ae._.js.map
   │  │  │  │  ├─ [root of the server]__e237d7._.js
   │  │  │  │  ├─ [root of the server]__e237d7._.js.map
   │  │  │  │  ├─ [root of the server]__e84423._.js
   │  │  │  │  ├─ [root of the server]__e84423._.js.map
   │  │  │  │  ├─ [root of the server]__eac902._.js
   │  │  │  │  ├─ [root of the server]__eac902._.js.map
   │  │  │  │  ├─ [root of the server]__f98774._.js
   │  │  │  │  ├─ [root of the server]__f98774._.js.map
   │  │  │  │  ├─ [turbopack]_runtime.js
   │  │  │  │  ├─ [turbopack]_runtime.js.map
   │  │  │  │  ├─ _119d67._.js
   │  │  │  │  ├─ _119d67._.js.map
   │  │  │  │  ├─ _11a950._.js
   │  │  │  │  ├─ _11a950._.js.map
   │  │  │  │  ├─ _2267de._.js
   │  │  │  │  ├─ _2267de._.js.map
   │  │  │  │  ├─ _2b1e72._.js
   │  │  │  │  ├─ _2b1e72._.js.map
   │  │  │  │  ├─ _2b89d5._.js
   │  │  │  │  ├─ _2b89d5._.js.map
   │  │  │  │  ├─ _497f52._.js
   │  │  │  │  ├─ _497f52._.js.map
   │  │  │  │  ├─ _549f33._.js
   │  │  │  │  ├─ _549f33._.js.map
   │  │  │  │  ├─ _573963._.js
   │  │  │  │  ├─ _573963._.js.map
   │  │  │  │  ├─ _59057a._.js
   │  │  │  │  ├─ _59057a._.js.map
   │  │  │  │  ├─ _6dd94a._.js
   │  │  │  │  ├─ _6dd94a._.js.map
   │  │  │  │  ├─ _71a62f._.js
   │  │  │  │  ├─ _71a62f._.js.map
   │  │  │  │  ├─ _889ba2._.js
   │  │  │  │  ├─ _889ba2._.js.map
   │  │  │  │  ├─ _8e1145._.js
   │  │  │  │  ├─ _8e1145._.js.map
   │  │  │  │  ├─ _a227eb._.js
   │  │  │  │  ├─ _a227eb._.js.map
   │  │  │  │  ├─ _ad2ed5._.js
   │  │  │  │  ├─ _ad2ed5._.js.map
   │  │  │  │  ├─ _bc5696._.js
   │  │  │  │  ├─ _bc5696._.js.map
   │  │  │  │  ├─ _caf2fa._.js
   │  │  │  │  ├─ _caf2fa._.js.map
   │  │  │  │  ├─ _d0bced._.js
   │  │  │  │  ├─ _d0bced._.js.map
   │  │  │  │  ├─ _d2c2f3._.js
   │  │  │  │  ├─ _d2c2f3._.js.map
   │  │  │  │  ├─ _d6fca9._.js
   │  │  │  │  ├─ _d6fca9._.js.map
   │  │  │  │  ├─ _e30902._.js
   │  │  │  │  ├─ _e30902._.js.map
   │  │  │  │  ├─ _e63cfa._.js
   │  │  │  │  └─ _e63cfa._.js.map
   │  │  │  ├─ [root of the server]__022459._.js
   │  │  │  ├─ [root of the server]__022459._.js.map
   │  │  │  ├─ [turbopack]_runtime.js
   │  │  │  └─ [turbopack]_runtime.js.map
   │  │  ├─ interception-route-rewrite-manifest.js
   │  │  ├─ middleware-build-manifest.js
   │  │  ├─ middleware-manifest.json
   │  │  ├─ middleware-react-loadable-manifest.js
   │  │  ├─ next-font-manifest.js
   │  │  ├─ next-font-manifest.json
   │  │  ├─ pages
   │  │  │  ├─ _app
   │  │  │  │  ├─ build-manifest.json
   │  │  │  │  ├─ next-font-manifest.json
   │  │  │  │  ├─ pages-manifest.json
   │  │  │  │  └─ react-loadable-manifest.json
   │  │  │  ├─ _app.js
   │  │  │  ├─ _app.js.map
   │  │  │  ├─ _document
   │  │  │  │  ├─ next-font-manifest.json
   │  │  │  │  ├─ pages-manifest.json
   │  │  │  │  └─ react-loadable-manifest.json
   │  │  │  ├─ _document.js
   │  │  │  ├─ _document.js.map
   │  │  │  ├─ _error
   │  │  │  │  ├─ build-manifest.json
   │  │  │  │  ├─ next-font-manifest.json
   │  │  │  │  ├─ pages-manifest.json
   │  │  │  │  └─ react-loadable-manifest.json
   │  │  │  ├─ _error.js
   │  │  │  └─ _error.js.map
   │  │  ├─ pages-manifest.json
   │  │  ├─ server-reference-manifest.js
   │  │  └─ server-reference-manifest.json
   │  ├─ static
   │  │  ├─ chunks
   │  │  │  ├─ app_dashboard_layout_tsx_04199f._.js
   │  │  │  ├─ app_dashboard_layout_tsx_240bd3._.js
   │  │  │  ├─ app_dashboard_layout_tsx_61af54._.js
   │  │  │  ├─ app_dashboard_layout_tsx_b669f9._.js
   │  │  │  ├─ app_dashboard_layout_tsx_b669f9._.js.map
   │  │  │  ├─ app_dashboard_layout_tsx_fb2edb._.js
   │  │  │  ├─ app_dashboard_page_jsx_04199f._.js
   │  │  │  ├─ app_dashboard_page_jsx_3c62fd._.js
   │  │  │  ├─ app_dashboard_page_jsx_5ca5e6._.js
   │  │  │  ├─ app_dashboard_page_jsx_d52ec6._.js
   │  │  │  ├─ app_dashboard_page_jsx_f5978e._.js
   │  │  │  ├─ app_dashboard_page_jsx_fb2edb._.js
   │  │  │  ├─ app_dashboard_users_page_tsx_2f511c._.js
   │  │  │  ├─ app_favicon_ico_mjs_53e3fe._.js
   │  │  │  ├─ app_globals_73c377.css
   │  │  │  ├─ app_globals_73c377.css.map
   │  │  │  ├─ app_globals_b52d8e.css
   │  │  │  ├─ app_globals_b52d8e.css.map
   │  │  │  ├─ app_layout_tsx_61af54._.js
   │  │  │  ├─ app_layout_tsx_83fc40._.js
   │  │  │  ├─ app_layout_tsx_83fc40._.js.map
   │  │  │  ├─ app_login_layout_tsx_04199f._.js
   │  │  │  ├─ app_login_layout_tsx_ceb06d._.js
   │  │  │  ├─ app_login_layout_tsx_d38420._.js
   │  │  │  ├─ app_login_layout_tsx_d38420._.js.map
   │  │  │  ├─ app_login_layout_tsx_fb2edb._.js
   │  │  │  ├─ app_login_page_tsx_03891a._.js
   │  │  │  ├─ app_login_page_tsx_04199f._.js
   │  │  │  ├─ app_login_page_tsx_0f3133._.js
   │  │  │  ├─ app_login_page_tsx_0f3133._.js.map
   │  │  │  ├─ app_login_page_tsx_390e21._.js
   │  │  │  ├─ app_login_page_tsx_86678f._.js
   │  │  │  ├─ app_login_page_tsx_867e8e._.js
   │  │  │  ├─ app_login_page_tsx_fb2edb._.js
   │  │  │  ├─ app_map_layout_tsx_469ea7._.js
   │  │  │  ├─ app_map_layout_tsx_469ea7._.js.map
   │  │  │  ├─ app_map_layout_tsx_845c4d._.js
   │  │  │  ├─ app_map_layout_tsx_ceb06d._.js
   │  │  │  ├─ app_map_layout_tsx_fb2edb._.js
   │  │  │  ├─ app_map_layout_tsx_fc0701._.js
   │  │  │  ├─ app_map_layout_tsx_fc0701._.js.map
   │  │  │  ├─ app_map_page_jsx_00ed3c._.js
   │  │  │  ├─ app_map_page_jsx_5134c5._.js
   │  │  │  ├─ app_map_page_jsx_c2ae95._.js
   │  │  │  ├─ app_map_page_jsx_ceb06d._.js
   │  │  │  ├─ app_map_page_jsx_ebc4e6._.js
   │  │  │  ├─ app_page_tsx_04199f._.js
   │  │  │  ├─ app_page_tsx_5210b7._.js
   │  │  │  ├─ app_page_tsx_5210b7._.js.map
   │  │  │  ├─ app_page_tsx_86678f._.js
   │  │  │  ├─ app_page_tsx_9fdd4f._.js
   │  │  │  ├─ app_page_tsx_9fdd4f._.js.map
   │  │  │  ├─ app_page_tsx_fb2edb._.js
   │  │  │  ├─ components_ShipRouteMap_client_jsx_0b63b4._.js
   │  │  │  ├─ components_ShipRouteMap_client_jsx_3402a6._.js
   │  │  │  ├─ components_ShipRouteMap_client_jsx_367b6f._.js
   │  │  │  ├─ components_ShipRouteMap_client_jsx_6c5af3._.js
   │  │  │  ├─ components_ShipRouteMap_client_jsx_6c5af3._.js.map
   │  │  │  ├─ components_ShipRouteMap_client_jsx_85ef84._.js
   │  │  │  ├─ components_ShipRouteMap_client_jsx_85ef84._.js.map
   │  │  │  ├─ components_ShipRouteMap_client_jsx_a0add6._.js
   │  │  │  ├─ components_ShipRouteMap_client_jsx_b81452._.js
   │  │  │  ├─ components_ShipRouteMap_client_jsx_b81452._.js.map
   │  │  │  ├─ components_ShipRouteMap_client_jsx_c4f39a._.js
   │  │  │  ├─ components_ShipRouteMap_client_jsx_c4f39a._.js.map
   │  │  │  ├─ components_ShipRouteMap_client_jsx_ce2ac9._.js
   │  │  │  ├─ components_ShipRouteMap_client_jsx_ce2ac9._.js.map
   │  │  │  ├─ components_ShipRouteMap_client_jsx_d16402._.js
   │  │  │  ├─ components_ShipRouteMap_client_jsx_d16402._.js.map
   │  │  │  ├─ components_ShipRouteMap_client_jsx_f0ad40._.js
   │  │  │  ├─ components_ShipRouteMap_client_jsx_f204ca._.js
   │  │  │  ├─ components_ShipRouteMap_client_jsx_f204ca._.js.map
   │  │  │  ├─ components_ShipRouteMap_client_jsx_fd7671._.js
   │  │  │  ├─ pages
   │  │  │  │  ├─ _app.js
   │  │  │  │  └─ _error.js
   │  │  │  ├─ pages__app_5771e1._.js
   │  │  │  ├─ pages__app_f2320d._.js
   │  │  │  ├─ pages__app_f2320d._.js.map
   │  │  │  ├─ pages__error_5771e1._.js
   │  │  │  ├─ pages__error_b8c4c3._.js
   │  │  │  ├─ pages__error_b8c4c3._.js.map
   │  │  │  ├─ [next]_internal_font_google_55dcbe._.css
   │  │  │  ├─ [next]_internal_font_google_55dcbe._.css.map
   │  │  │  ├─ [next]_internal_font_google_geist_e531dabc_module_b52d8e.css
   │  │  │  ├─ [next]_internal_font_google_geist_e531dabc_module_b52d8e.css.map
   │  │  │  ├─ [next]_internal_font_google_geist_mono_68a01160_module_b52d8e.css
   │  │  │  ├─ [next]_internal_font_google_geist_mono_68a01160_module_b52d8e.css.map
   │  │  │  ├─ [root of the server]__2e1cf5._.js
   │  │  │  ├─ [root of the server]__2e1cf5._.js.map
   │  │  │  ├─ [root of the server]__31723f._.js
   │  │  │  ├─ [root of the server]__31723f._.js.map
   │  │  │  ├─ [root of the server]__9d1267._.css
   │  │  │  ├─ [root of the server]__9d1267._.css.map
   │  │  │  ├─ [root of the server]__f265a1._.js
   │  │  │  ├─ [root of the server]__f265a1._.js.map
   │  │  │  ├─ [root of the server]__f81d50._.js
   │  │  │  ├─ [root of the server]__f81d50._.js.map
   │  │  │  ├─ [turbopack]_browser_dev_hmr-client_d6d8d4._.js
   │  │  │  ├─ [turbopack]_browser_dev_hmr-client_d6d8d4._.js.map
   │  │  │  ├─ [turbopack]_browser_dev_hmr-client_hmr-client_ts_8e6352._.js
   │  │  │  ├─ [turbopack]_browser_dev_hmr-client_hmr-client_ts_d0a96d._.js
   │  │  │  ├─ [turbopack]_browser_dev_hmr-client_hmr-client_ts_d0a96d._.js.map
   │  │  │  ├─ _10149c._.js
   │  │  │  ├─ _10149c._.js.map
   │  │  │  ├─ _22d2ba._.js
   │  │  │  ├─ _22d2ba._.js.map
   │  │  │  ├─ _4d2fc1._.js
   │  │  │  ├─ _4d2fc1._.js.map
   │  │  │  ├─ _51a7c0._.js
   │  │  │  ├─ _51a7c0._.js.map
   │  │  │  ├─ _8badbf._.js
   │  │  │  ├─ _8badbf._.js.map
   │  │  │  ├─ _8c5373._.js
   │  │  │  ├─ _8c5373._.js.map
   │  │  │  ├─ _8ef6ff._.js
   │  │  │  ├─ _8ef6ff._.js.map
   │  │  │  ├─ _911a7a._.js
   │  │  │  ├─ _911a7a._.js.map
   │  │  │  ├─ _9f3656._.js
   │  │  │  ├─ _9f3656._.js.map
   │  │  │  ├─ _a03f48._.js
   │  │  │  ├─ _a03f48._.js.map
   │  │  │  ├─ _a24be7._.js
   │  │  │  ├─ _a24be7._.js.map
   │  │  │  ├─ _b38a4d._.js
   │  │  │  ├─ _b38a4d._.js.map
   │  │  │  ├─ _c63f0b._.js
   │  │  │  ├─ _c63f0b._.js.map
   │  │  │  ├─ _d95469._.js
   │  │  │  ├─ _d95469._.js.map
   │  │  │  ├─ _ddb7ea._.js
   │  │  │  ├─ _ddb7ea._.js.map
   │  │  │  ├─ _e07334._.js
   │  │  │  ├─ _e07334._.js.map
   │  │  │  ├─ _e09ed7._.js
   │  │  │  ├─ _e09ed7._.js.map
   │  │  │  ├─ _e225a2._.js
   │  │  │  ├─ _e225a2._.js.map
   │  │  │  ├─ _e69f0d._.js
   │  │  │  ├─ _ec063f._.js
   │  │  │  ├─ _ec063f._.js.map
   │  │  │  ├─ _f3837e._.js
   │  │  │  └─ _f3837e._.js.map
   │  │  ├─ development
   │  │  │  ├─ _buildManifest.js
   │  │  │  ├─ _clientMiddlewareManifest.json
   │  │  │  └─ _ssgManifest.js
   │  │  └─ media
   │  │     ├─ favicon.45db1c09.ico
   │  │     ├─ gyByhwUxId8gMEwcGFWNOITd-s.p.da1ebef7.woff2
   │  │     ├─ gyByhwUxId8gMEwSGFWNOITddY4-s.81df3a5b.woff2
   │  │     ├─ or3nQ6H_1_WfwkMZI_qYFrcdmhHkjko-s.p.be19f591.woff2
   │  │     └─ or3nQ6H_1_WfwkMZI_qYFrkdmhHkjkotbA-s.e32db976.woff2
   │  ├─ trace
   │  ├─ transform.js
   │  ├─ transform.js.map
   │  └─ types
   ├─ app
   │  ├─ dashboard
   │  │  ├─ data-analysis
   │  │  │  └─ page.tsx
   │  │  ├─ data-upload
   │  │  │  └─ page.tsx
   │  │  ├─ feedback
   │  │  │  └─ page.tsx
   │  │  ├─ layout.tsx
   │  │  ├─ users
   │  │  │  └─ page.tsx
   │  │  └─ vessel-status
   │  │     └─ page.tsx
   │  ├─ favicon.ico
   │  ├─ globals.css
   │  ├─ layout.tsx
   │  ├─ login
   │  │  ├─ layout.tsx
   │  │  └─ page.tsx
   │  ├─ map
   │  │  ├─ layout.tsx
   │  │  └─ page.jsx
   │  └─ page.tsx
   ├─ components
   │  ├─ AuthGuard.tsx
   │  ├─ icons.tsx
   │  ├─ Navbar.tsx
   │  ├─ shell
   │  │  ├─ header.tsx
   │  │  ├─ icons.tsx
   │  │  ├─ nav-items.ts
   │  │  ├─ shell.tsx
   │  │  └─ sidebar.tsx
   │  ├─ ShipRouteMap.client.jsx
   │  ├─ Sidebar.tsx
   │  ├─ tables
   │  │  └─ user-table.tsx
   │  ├─ ui
   │  │  ├─ button.tsx
   │  │  ├─ drawer.tsx
   │  │  ├─ sheet.tsx
   │  │  └─ table.tsx
   │  └─ VesselTypePieChart.jsx
   ├─ components.json
   ├─ contexts
   │  └─ AuthContext.tsx
   ├─ eslint.config.mjs
   ├─ hooks
   ├─ lib
   │  └─ utils.ts
   ├─ next-env.d.ts
   ├─ next.config.ts
   ├─ package-lock.json
   ├─ package.json
   ├─ postcss.config.mjs
   ├─ public
   │  ├─ file.svg
   │  ├─ globe.svg
   │  ├─ next.svg
   │  ├─ vercel.svg
   │  └─ window.svg
   ├─ README.md
   ├─ tailwind.config.ts
   ├─ tsconfig.json
   ├─ types
   │  └─ authGuard.ts
   └─ utils

```
=======
# gp2
>>>>>>> f0e069321b16622af9e4787f3dea25379182bef8
