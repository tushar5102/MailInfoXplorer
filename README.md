# Email Information Extractor

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

**Author**: Tushar Santosh Patil

**Email**: tushar.patil.5202@gmail.com

The Email Information Extractor is a Python script designed for extracting essential information from email messages. It provides detailed insights into email metadata, including sender, recipient, subject, timestamp, routing data, attachments, and a summary of email content. This tool is valuable for email analysis and processing tasks.

## Features

- **Sender Information:** Extracts the sender's email address.

- **Recipient Information:** Retrieves the recipient's email address.

- **Subject Decoding:** Decodes the subject line, if encoded.

- **Timestamp Parsing:** Parses the timestamp in various common formats.

- **Routing Information:** Extracts routing data, such as Received headers.

- **Attachment Handling:** Extracts and optionally saves email attachments.

- **Content Summary:** Provides a summary of the email content.

## Prerequisites

- Python 3.x
- Standard Python libraries: `sys`, `email`, `email.header`, `datetime`, `os`


## Installation

To use the Email Information Extractor, follow these steps:

1. **Download the Script:** Download the script from the repository or clone the entire repository to your local machine.

2. **Run the Script:** Open your terminal and navigate to the directory where you downloaded the script or where you cloned the repository.

3. **Execute the Script:** Run the script by entering the following command, replacing `<email_file>` with the actual path to the email file you want to analyze:

   ```bash
   python email_info_extractor.py <email_file> [attachment_dir]

- `<email_file>`: The path to the email file you want to analyze.
- `[attachment_dir]` (optional): The directory where you want to save email attachments. If not provided, attachments won't be saved.



## Usage

To utilize the Email Information Extractor, follow these simple steps:

1. **Execute the Script:** Run the script with the path to the email file as an argument to initiate the extraction of metadata and information.

    ```bash
    python email_info_extractor.py <email_file> [attachment_dir]
    ```

   - `<email_file>`: Specify the path to the email file you intend to analyze.
   - `[attachment_dir]` (optional): Optionally, you can provide the directory where you want to store email attachments. If this argument is omitted, attachments won't be saved.

2. **Review Output:** Upon execution, the script will present the following extracted metadata:

   - Sender's information
   - Recipient's information
   - Subject of the email (decoded if encoded)
   - Timestamp (parsed in multiple common formats)
   - Routing information (e.g., Received headers)
   - A concise summary of the email's content

   Furthermore, it has the capability to save attachments if an `attachment_dir` is specified during execution.

The Email Information Extractor streamlines the process of analyzing email files, making it a valuable tool for email data extraction and thorough examination.



## Example

This will extract email information from sample_email.eml, save any attachments to the output_attachments directory, and display the results.
Here's an example command to run the script:


    python email_info_extractor.py sample_email.eml output_attachments






## License

SystemGuardian is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the script in accordance with the terms of this license.

## Disclaimer

Please note that the SystemGuardian script is provided as-is, without any warranty or guarantee. Use it at your own risk. Always review the code and understand the actions it performs before running it on your system.
