# AutoBannerSlider 🎉

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE) 
[![GitHub stars](https://img.shields.io/github/stars/Moin06-dev/AutoBannerSlider)](https://github.com/Moin06-dev/AutoBannerSlider/stargazers) 
[![GitHub forks](https://img.shields.io/github/forks/Moin06-dev/AutoBannerSlider)](https://github.com/Moin06-dev/AutoBannerSlider/network)

AutoBannerSlider is an easy-to-use, customizable banner slider for web applications. 🚀 It helps you create stunning banner slideshows with minimal effort. 

## Features ✨

- **Auto Slide**: Automatically transitions between banners at a set interval ⏲️
- **Customizable**: Easily change the transition effects, timings, and more 🎨
- **Responsive**: Works seamlessly on all devices, ensuring your banners look great everywhere 📱💻
- **Lightweight**: Minimal impact on your page load times ⚡
- **Easy Integration**: Simple setup and integration with your existing projects 🛠️

## Installation 📦

1. Clone the repository:
   ```bash
   git clone https://github.com/Moin06-dev/AutoBannerSlider.git
   ```

2. Navigate to the project directory:
   ```bash
   cd AutoBannerSlider
   ```

3. Include the CSS and JS files in your project:
   ```html
   <link rel="stylesheet" href="path/to/autobannerslider.css">
   <script src="path/to/autobannerslider.js"></script>
   ```

## Usage 📖

1. Add the HTML structure for your banner slider:
   ```html
   <div class="autobannerslider">
       <div class="slide">Slide 1</div>
       <div class="slide">Slide 2</div>
       <div class="slide">Slide 3</div>
   </div>
   ```

2. Initialize the slider in your JavaScript:
   ```javascript
   document.addEventListener('DOMContentLoaded', () => {
       AutoBannerSlider.init({
           selector: '.autobannerslider',
           interval: 3000,
           transitionEffect: 'fade'
       });
   });
   ```

## Customization 🎨

You can customize the slider by passing options to the `init` method:

- `selector` (string): The CSS selector for the banner slider container.
- `interval` (number): Time in milliseconds between slide transitions.
- `transitionEffect` (string): The transition effect for slides ('fade', 'slide', etc.).

Example:
```javascript
AutoBannerSlider.init({
    selector: '.autobannerslider',
    interval: 5000,
    transitionEffect: 'slide'
});
```

## Contributing 🤝

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Connect with me 🌐

- [GitHub](https://github.com/Moin06-dev)
