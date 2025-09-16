## Petclinic Application Details

The Petclinic application is a Spring Boot application that runs on port 8080.

### Application Image:

- Image: facetscloud/petclinic:1.0

### Running with Postgres:

To run the Petclinic application with Postgres, you need to set the following environment variables:

- `SPRING_PROFILES_ACTIVE: "postgres"`
- `POSTGRES_URL: "jdbc:postgresql://<POSTGRES_HOST>:<POSTGRES_PORT>/dbname?sslmode=require"`
- `POSTGRES_USER: "<POSTGRES_USERNAME>"`
- `POSTGRES_PASS: "<POSTGRES_PASSWORD>"`

Please replace `<POSTGRES_HOST>`, `<POSTGRES_USERNAME>`, and `<POSTGRES_PASSWORD>` with the actual host, username, and password of your Postgres database.

Remember to secure your `POSTGRES_USER` and `POSTGRES_PASS` as they are sensitive information related to your database.

With these settings, the Petclinic application will be able to persist data using the Postgres database.
