![Banner](banner.png)

# file-similarity-analyzer
Calculates a similarity score between two files using fuzzy hashing (e.g., ssdeep). Useful for identifying near-duplicate files or detecting code reuse. - Focused on File operations and analysis

## Install
`git clone https://github.com/ShadowStrikeHQ/file-similarity-analyzer`

`cd file-similarity-analyzer`

`pip install -r requirements.txt`

The `ssdeep` Python library listed in `requirements.txt` is required. If it is missing, the tool exits 1 with a plain line naming the missing library and the install command, with no traceback.

## Usage
`python3 main.py file1 file2 [-l LOG_LEVEL]`

## Parameters
- `file1`: Path to the first file (positional, required)
- `file2`: Path to the second file (positional, required)
- `-h`: Show help message and exit
- `-l`, `--log_level`: Set the logging level (default: INFO)

## License
Copyright (c) ShadowStrikeHQ
