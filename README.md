# PDUDecoder - A Python Class for GSM 7-bit PDU Decoding

## Overview
The `PDUDecoder` class provides a simple yet effective way to decode GSM 7-bit PDU (Protocol Data Unit) encoded text in Python. It supports both the standard GSM character set and the extended character set.

## Features
- **Decoding of GSM 7-bit PDU**: Converts PDU encoded text into a human-readable string.
- **GSM and Extended Character Sets**: Includes a comprehensive list of characters supported in the GSM and extended GSM character sets.

## Installation
This class does not require any external dependencies. You can simply copy the `PDUDecoder` class into your Python project.

## Usage

### Example
Here's a basic example of how to use the `PDUDecoder` class:

```python
# Import the class
from pdu_decoder import PDUDecoder

# Example PDU encoded text (as a string of hex characters)
encoded_text = "E8329BFD4697D9EC37"

# Decode the PDU encoded text
decoded_text = PDUDecoder.pdu_to_string(encoded_text)

# Print the decoded text
print("Decoded text:", decoded_text)
```

## Decoding Functionality
To decode a string of PDU encoded text, use the pdu_to_string static method. This method takes a string of hex characters representing the PDU encoded text and returns the decoded string.


## Contributions
Contributions to this project are welcome. Please ensure that any pull requests are well-documented and include unit tests where applicable.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
