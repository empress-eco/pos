<div align="center">
    <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Project Logo">
    <h1 align="center">POS Awesome: Powering Your Retail Operations</h1>
</div>

<p align="center">
    Enhance your retail operations with POS Awesome, a robust, user-friendly, and open-source point of sale application designed for businesses of all sizes.
    <br />
    <a href="https://grow.empress.eco/">Explore the Docs</a>
    ·
    <a href="https://github.com/empress-eco/pos/issues">Report Bug</a>
    ·
    <a href="https://github.com/empress-eco/pos/issues">Request Feature</a>
</p>

## About The Project

### 📖 Overview
POS Awesome is a versatile retail solution that supports a wide range of features, from customer loyalty points to batch-based pricing. It is designed to make your retail operations more efficient and user-friendly.

### 🌟 Key Features
- User-friendly interface with list or card view options
- Enqueue invoice submission and batch & serial numbering
- UOM specific barcode and pricing
- Process POS returns
- Supports credit sales and customer loyalty points
- Accepts new payments from customers against existing invoices

### 🛠 Built With
POS Awesome is built using major frameworks and libraries:
- [Vue.js](https://github.com/vuejs/vue)
- [Vuetify.js](https://github.com/vuetifyjs/vuetify)

## Getting Started

### Prerequisites
You'll need to have Empress Version 14 installed to get started with POS Awesome.

### Installation
To set up a development environment, follow these steps:

```sh
# Clone the repository
git clone https://github.com/empress-eco/pos.git

# Navigate to the repository
cd pos

# Setup requirements
bench setup requirements

# Build the app
bench build --app posawesome

# Restart the bench
bench restart

# Install the app
bench --site [your.site.name] install-app posawesome

# Migrate the site
bench --site [your.site.name] migrate
```

## Usage
For detailed usage instructions, visit the [POS Awesome Documentation](https://grow.empress.eco/).

## Contributing
We welcome contributions! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License and Acknowledgments

### License
This project is under the MIT License. Your contributions are also licensed under the MIT License.

### Acknowledgments
We extend our gratitude to [Empress](https://github.com/Empress/Empress) and [Empress](https://github.com/Empress/Empress) developers and contributors for laying the groundwork for this project. We appreciate their innovative work and continued support.
