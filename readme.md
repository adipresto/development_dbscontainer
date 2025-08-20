# Proceed with caution
For personal development on Windows, you can use portable runtimes such as Laragon to run a database without containers.


However, for team development or production deployment, using containers (e.g., Docker or Podman) is recommended since they provide a more consistent, replicable, and isolated environment.

## Ports
| Service      | Default Port | Host Access (localhost) | Notes                                                                       |
| ------------ | ------------ | ----------------------- | --------------------------------------------------------------------------- |
| **MySQL**    | `3306`       | `localhost:3306`        | Accessible from apps/DB clients (e.g., MySQL Workbench, DBeaver).           |
| **Postgres** | `5432`       | `localhost:5432`        | Accessible from apps/DB clients (e.g., psql, DBeaver).                      |
| **MongoDB**  | `27017`      | `localhost:27017`       | Accessible from MongoDB clients (e.g., MongoDB Compass, mongosh).           |
| **Adminer**  | `8080`       | `http://localhost:8080` | Web-based GUI for managing databases (MySQL & PostgreSQL, **not MongoDB**). |
