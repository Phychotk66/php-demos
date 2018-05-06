# Shotstack PHP Examples

- **images.php** -
    Takes an array of Instagram image URLs and creates a video with a soundtrack 
    and simple zoom in effect.
    
- **text.php** -
    Create a HELLO WORLD video title against black background with a soundtrack.
    
- **status.php** -
    Shows the status of a render task and the output video URL. Run this after running one of the render examples.
    
### Installation

Install the required dependencies including the [Shotstack SDK](https://packagist.org/packages/shotstack/shotstack-sdk-php)

```bash
composer install
```

### Set your API key

```bash
export SHOTSTACK_KEY=your_key_here
```

### Run an example

The examples directory includes a number of examples demonstrating the capabilities of the 
Shotstack API.

To run the images example:

```bash
php examples/images.php
```