## City Air Quality script

This is a Rust script that retrieves and logs data about a city's air quality.

### Prerequisites

- Rust. ([installation guide](https://www.rust-lang.org/tools/install)).
- aqicn.org API token. You can generate it by signing up on [https://aqicn.org/data-platform/token/](https://aqicn.org/data-platform/token/).

### Usage

To use this program, follow these steps:

1. Create a `.env` file in the project's root directory.
2. Inside the `.env` file, add the following line:

```
API_TOKEN=<your-api-token>
```

Replace `<your-api-token>` with the API token you generated from [https://aqicn.org/data-platform/token/](https://aqicn.org/data-platform/token/).

3. Run the program with the following command:

```
cargo run -- san francisco
```

Replace `San Francisco` with the name of the city for which you want to fetch data.

4. The program will log a response from the API or error message.

### Example

Here's an example command to run the program:

```
cargo run -- "San Francisco"
```

This command will fetch data about the city of San Francisco and log the data in a pretty format.

### Acknowledgements

This project is part of Chris Biscardi's Rust course. Credit to Chris Biscardi for providing the educational materials for this project.
