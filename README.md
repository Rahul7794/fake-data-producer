# Fake Data Producer

The **Fake Data Producer** is a versatile tool designed to generate synthetic data for various purposes, such as testing, development, and data analysis. This command-line application empowers you to effortlessly create realistic datasets with customizable data types, ranges, and formats. Whether you're populating databases, validating software, or exploring data pipelines, the Fake Data Producer streamlines the process of generating diverse data that mimics real-world scenarios. With support for a wide range of data types and customization options, you can tailor your generated data to match your specific use case.

## Key Features

- **Configurable Data Generation:** Define your dataset's structure using an intuitive JSON configuration. Specify data types, ranges, and additional parameters to precisely control the generated content.

- **Rich Data Types:** The Fake Data Producer supports various data types, including strings, integers, floating-point numbers, booleans, timestamps, and more. Customizable options like "options" for strings and "min/max" for numeric values offer fine-grained control.

- **Realistic Field Generators:** Leveraging the power of the gofakeit library, the Fake Data Producer employs sophisticated field generators to create authentic and diverse data for different columns.

- **Dynamic Output Formats:** Generate data in multiple formats such as CSV, Kafka messages, or even directly to the console. Seamlessly integrate the generated data into your preferred workflows and systems.

- **Easy Integration:** Integrate the Fake Data Producer into your development and testing processes using a simple command-line interface. Effortlessly generate datasets with a few commands, allowing you to focus on more critical aspects of your project.

### dependencies

- [gofakeit](https://github.com/brianvoe/gofakeit): Random data generator written in go

### Configuration

[here](conf/readme.md)

### Usage

- [kafka producer](cmd/kafka/readme.md)
- [csv producer](cmd/csv/readme.md)
- [console_producer](cmd/console/readme.md)

