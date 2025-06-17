# Emotion Analysis MCP Server

Welcome to the Emotion Analysis MCP Server, a powerful tool designed to detect and analyze emotions within a block of text. This server helps you understand the emotional tone of any paragraph by providing a comprehensive breakdown of emotions such as disgust, sadness, anger, joy, surprise, and fear.

## Overview

The Emotion Analysis MCP Server allows users to identify the emotional context within a given text. Whether you're analyzing customer feedback, social media content, or any other form of textual data, this server can provide valuable insights into the emotions expressed.

### Key Features

- **Emotion Detection**: Analyze a paragraph of text to identify the presence of six key emotions: disgust, sadness, anger, joy, surprise, and fear.
- **High Performance**: The server is designed to handle up to 6 requests per second under normal conditions and can scale up to 300 requests per second during high traffic periods.
- **Security and Privacy**: We prioritize your privacy and security. No content is stored on our servers; only transaction logs are maintained. We recommend using the POST method to further ensure data security.

## Usage

### Tools

The Emotion Analysis MCP Server provides the following tools for emotion detection:

1. **Analyze (POST)**
   - Function: `analyze`
   - Description: Detect the emotions of a paragraph of text using a secure POST request method.

2. **Analyze (GET)**
   - Function: `analyze`
   - Description: Detect the emotions of a paragraph of text using a GET request method.

### API Limitations

- **Max Input Size**: The server can process text up to 14,336 Unicode characters, including whitespace and any markup characters.
- **Rate Limitations**: While there is no specific rate limit, it is recommended to start at 6 requests per second and gradually increase to avoid request failures.
- **Server Capacity**: The server automatically scales based on traffic, but it is advisable to increase request rates gradually to ensure optimal performance.

## Security and Compliance

Our server adheres to strict security and privacy standards. We conduct regular PCI compliance checks through third-party assessments to ensure data protection. For enhanced security, we advise using the POST method when submitting text for analysis.

## Conclusion

The Emotion Analysis MCP Server is an essential tool for anyone looking to gain insights into the emotional tone of textual data. By leveraging this server, you can better understand and respond to the emotions conveyed in written communication.