# Getting Started

Download or Generate MAVLink source files for your [dialect](../messages/index.md#dialects):

- **Download the [pre-built MAVLink source files](../index.md#prebuilt_libraries)** if you're working in a C/C++ project and using standard dialects.
- **Generate the MAVLink source files** to use any other [supported language](../index.md#supported_languages), add/modify messages or dialects, or use the example scripts:
  1. [Install MAVLink](../getting_started/installation.md)
  2. [Generate Language-Specific Source Files](../getting_started/generate_libraries.md).

以下内容将说明，如何将生成的相关文件包含在项目中，并使用 MAVLink:

- [Use the MAVLink Source Files](../getting_started/use_libraries.md) explains how to include the source files in your project and send messages.
- [Message Definitions](../messages/index.md) contains human-readable explanations of the messages.
- [Microservices](../services/index.md) explains the main sub-protocols for working with missions, cameras, images, parameters etc.