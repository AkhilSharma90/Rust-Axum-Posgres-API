# Rust CRUD API Example with Axum and PostgreSQL

![YouTube Channel Subscribers](https://img.shields.io/youtube/channel/subscribers/UCgMjDy6Y7WISZ529S4VyXUg)
[![LinkedIn][linkedin-shield]][linkedin-url]

Akhil - A quick CRUD API with Axum and postgres. A follow up of my 2 videos on Rust and Postgres. All of this will be in the 50 Rust project playlist on my channel - https://www.youtube.com/playlist?list=PL5dTjWUk_cPYuhHm9_QImW7_u4lr5d6zO



## Topics Covered

- Run the Axum PostgreSQL API Locally
- Run the Axum API with a Frontend Application
- Setup the Axum and Rust Project
- Setup Postgres and pgAdmin Servers with Docker
- Run Database Migrations with SQLx-CLI
    - Connect to the Postgres Server with SQLx
- Create the SQLX Database Model
- Create the Request Validation Structs
- Implement the CRUD Functionalities
    - Axum Route Handler to Fetch All Records
    - Axum Route Handler to Add a Record
    - Axum Route Handler to Fetch a Record
    - Axum Route Handler to Edit a Record
    - Axum Route Handler to Delete a Record
    - The Complete Axum Route Handlers
- Create the CRUD API Endpoints
- Register the Axum Router and Setup CORS
- Conclusion

### Installation
1. Clone the repo
   ```sh
   git clone https://github.com/akhilsharma90/Rust-Axum-Postgres-API.git
   ```
2. Build the project to install the dependecies
   ```sh
   cargo build
   ```
4. Run with
   ```sh
   cargo run
   ```
   Or, for more dynamic development, run in watch mode
   ```sh
   cargo watch -q -c -w src/ -x run
   ```
   `-q` quiet mode <br>
   `-c` clear the console on reload <br>
   `-w` watch all change to files under `src/` <br>
   `-x` executes `run` command

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'feat: add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- CONTACT -->
## Contact

Akhil Sharma - [@akhilairi](https://twitter.com/AkhilAiri) - akhil.sharma@myrl.tech

Project Link: [https://github.com/akhilsharma90/rust_axum_postgres_API](https://github.com/AkhilSharma90/Rust-Axum-Posgres-API)