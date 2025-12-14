# Boa

The Boa programming language.

## Building and running the Boa compiler

- Install [Coursier](https://get-coursier.io/).
- Install `sbt` and `scala3` with Coursier:

    ```sh
    coursier install sbt scala3
    ```

- Run the project:

    ```sh
    sbt run
    ```

- Run the project (with watch mode enabled):

    ```sh
    sbt ~run
    ```

- Build the project for production:

    ```sh
    sbt assembly
    ```

    The generated JAR is located in the `target/scala-<version>` folder.
