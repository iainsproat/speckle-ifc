# speckle-ifc

An IFC to Speckle converter.

## License

The license is GPL because of the IfcOpenShell dependency. Please fully understand the implications of using this code in your project before doing so. You may have to release your code as open source if you use this code or in your project. Please seek professional legal advice.

## Usage

### Setup

1. Please ensure Python 3.9 or greater is installed in the environment in which you wish to run this tool, but 3.12 is not yet supported by ifcopenshell.
1. Install [Python Poetry](https://python-poetry.org/docs/#installation).
1. Download or clone this repository.
1. Install the required packages by running `poetry install` in the root of the repository.
1. Run the tool using the instructions below.

### Importing an IFC file to Speckle

```bash
poetry run python cmd/ifc_to_speckle.py --input <path_to_ifc_file.ifc> --config <path_to_config_file.yml> --mapping <path_to_mapping_file.yml>
```

### Exporting from Speckle to an IFC file

```bash
echo "Not implemented yet (Duke Nukem Forever?)."
```

## Feature support

Absolutely nothing is implemented yet. This is a work in progress.

| Feature | Supported | Notes |
|---------|-----------|-------|
| Your mama | ❌ | Unsupportable |

## Development

Incantations to the Python gods.

1. Please ensure Python 3.9 or greater is installed in the environment in which you wish to run this tool, but 3.12 is not yet supported by ifcopenshell.
1. Download or clone this repository.
1. Install [Python Poetry](https://python-poetry.org/docs/#installation).
1. Install [pre-commit](https://pre-commit.com/).
1. Install the pre-commit hooks by running `pre-commit install` in the root of the repository.
