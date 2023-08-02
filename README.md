# Customer_Testimonial_Slider.
"Slider Testimonial: A captivating web app showcasing customer reviews with profile pictures and ratings. User-friendly slider for easy navigation. Responsive design for seamless viewing. HTML, CSS, and JS blend to create an attractive testimonial display."


# Slider Testimonial Documentation

## Introduction

The Slider Testimonial project is a web application that showcases testimonials from customers who have used our platform. It provides a user-friendly interface to display customer reviews along with their names and profile pictures. The testimonial slider allows users to navigate through different customer reviews easily.

## Technologies Used

The project utilizes the following technologies:

- HTML: To structure the web page.
- CSS: To style the elements and layout.
- JavaScript: To handle customer data and implement the testimonial slider functionality.
- Google Fonts API: To import and use custom fonts for better typography.
- Font Awesome: To display star icons for ratings.

## HTML Structure

The HTML file contains the following elements:

- `<h3>`: A heading displaying "What our Client Say."
- `<h5>`: A subheading showing "Client's Review after using our Platform."
- `<div class="container">`: A container to hold the testimonial card.
- `<div class="card">`: A card displaying customer details and review.
- `<img id="customer-img">`: An image displaying the customer's profile picture.
- `<h4 class="customer-name">`: The customer's name.
- `<div class="review">`: A container to display star icons for the customer's rating.
- `<p id="customer-text">`: The customer's review text.
- `<a class="btn nextBtn">` and `<a class="btn prevBtn">`: Buttons to navigate to the next and previous testimonials.

## CSS Styling

The CSS file contains styles to achieve a visually appealing design for the testimonial card and the overall layout of the web page. It sets the font family, background color, padding, and spacing for various elements.

## JavaScript Functionality

The JavaScript file provides the functionality to handle customer data and implement the testimonial slider. It contains the following functions:

- `updateCustomerDetails()`: Updates the testimonial card with the details of the current customer (name, image, and review).
- `nextCustomer()`: Moves to the next customer in the list and updates the testimonial card accordingly.
- `prevCustomer()`: Moves to the previous customer in the list and updates the testimonial card accordingly.
- Event Listeners: Adds event listeners to the "Next" and "Previous" buttons to trigger the corresponding functions when clicked.
- Initialization: Initializes the first customer details on page load.

## Customer Data

The project includes an array named `customers`, which stores information about different customers. Each customer object contains the following properties:

- `name`: The name of the customer.
- `image`: The URL of the customer's profile picture.
- `review`: The review text provided by the customer.

## Responsiveness

The web page is designed to be responsive and adjusts its layout for different screen sizes. Media queries are used to adapt the testimonial card's width and other properties for smaller devices.

## Conclusion

The Slider Testimonial project is a simple yet effective way to display customer reviews and feedback for our platform. With its user-friendly interface and responsive design, it offers a seamless experience for users to explore the testimonials. The combination of HTML, CSS, and JavaScript brings life to the project, making it an attractive addition to our platform's landing page.
