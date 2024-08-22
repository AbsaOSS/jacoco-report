# JaCoCo Report
Github action that publishes the JaCoCo report as a comment in the Pull Request.

## Description
The **JaCoCo Report** GitHub Action is designed to publish the JaCoCo code coverage report as a comment in the Pull Request. It provides a detailed overview of the code coverage, highlighting the percentage of lines, branches, and methods covered by the tests. This action helps developers and reviewers assess the quality of the codebase and identify areas that require additional testing.

## How It Works
TODO

## Inputs
### `TODO`
- **Description**: TODO
- **Required**: Yes
- **Example**: `TODO`

### `verbose-logging`
- **Description**: Enable verbose logging to provide detailed output during the action’s execution, aiding in troubleshooting and setup.
- **Required**: No
- **Default**: `false`
- **Note**: If workflow run in debug mode, 'verbose-logging' is set to 'true.'

### `fail-on-violation`
- **Description**: Set to true to fail the action if any convention violations are detected. Set false to continue without failure.
- **Required**: No
- **Default**: `false`

## Usage Example
### Default
```yaml
TODO
```

### Full example
```yaml
TODO
```

## How to build

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/AbsaOSS/jacoco-report.git
cd jacoco-report
```

Install the dependencies:
```bash
pip install -r requirements.txt
```


## Running Unit Tests
Unit tests are written using pytest. To run the tests, use the following command:

```bash
pytest
```

This will execute all tests located in the __tests__ directory and generate a code coverage report.

## Code Coverage
Code coverage is collected using pytest-cov coverage tool. To run the tests and collect coverage information, use the following command:

```bash
pytest --cov=jacoco_report --cov-report html tests/
```
See the coverage report on the path:
```bash
htmlcov/index.html
```

## Run Action Locally
Create *.sh file and place it in the project root.
```bash
#!/bin/bash

# Set environment variables based on the action inputs
export INPUT_TODO="TODO"

# Run the Python script
python3 ./jacoco_report/todo.py
```


## Contributing
Feel free to submit issues or pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details.
