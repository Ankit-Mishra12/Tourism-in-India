# 🇮🇳 Tourism in India Website

This is an attractive, frontend-only website project for a "Tourism in India" travel service. It demonstrates a complete, simulated user journey—from browsing destinations and planning a trip to selecting attractions and completing a mock payment.

*(**Pro-Tip:** Add a screenshot of your project's home page here to make it look even better!)*

## ✨ Features

* **Beautiful Home Page:** A main dashboard (`home page.html`) featuring a grid of famous Indian tourist destinations.
* **User Authentication Flow:** Separate, styled pages for user **Login** (`login.html`) and **Registration** (`reg.html`).
* **Trip Planner:** A simple form (`location.html`) for users to input their starting location and desired destination.
* **Destination Pages:** Detailed pages for specific cities (like `agra.html` and `mumbai.html`) where users can:
    * Browse popular attractions (e.g., Taj Mahal, Gateway of India).
    * See the price for each attraction.
    * Select multiple attractions using checkboxes.
* **Dynamic Price Calculation:** A JavaScript function (`calculateTotal()`) automatically calculates the total bill in real-time based on the user's selected attractions.
* **Simulated Payment Flow:**
    * A payment gateway page (`payment.html`) with options for UPI, Credit Card, and Debit Card.
    * JavaScript logic to show the correct input fields for the selected payment method.
    * A final payment confirmation page (`lpc.html`) to complete the user's booking.

## 💻 Tech Stack

* **HTML5:** Used for the structure and content of all 8 pages.
* **CSS3:** Used for all styling, layout, background images, and attractive UI (all CSS is embedded within the `<style>` tags in each file).
* **JavaScript (Vanilla):** Used for client-side interactivity, including:
    * Calculating the total bill on the destination pages.
    * Showing/hiding the "Proceed to Payment" button after calculation.
    * Toggling payment detail fields on the payment gateway page.

## 🚀 How to Run This Project

Since this is a static website (frontend only), you can run it very easily.

1.  **Download or Clone the Repository**
    ```bash
    git clone [https://github.com/YOUR-USERNAME/tourism-in-india.git](https://github.com/YOUR-USERNAME/tourism-in-india.git)
    ```
2.  **Navigate to the Folder**
    ```bash
    cd tourism-in-india
    ```
3.  **Open the Main File**
    Open the **`home page.html`** file in your web browser.

    *(**Pro-Tip:** If you rename `home page.html` to `index.html`, you can easily host this project for free on GitHub Pages!)*

## 📂 File Structure
├── home page.html # The main landing page with destination cards ├── login.html # User login form ├── reg.html # User registration form ├── location.html # "Plan a Trip" location input form ├── agra.html # Destination page for Agra with attractions ├── mumbai.html # Destination page for Mumbai with attractions ├── payment.html # Payment gateway simulation page └── lpc.html # "Last Page Confirmation" (Payment Successful)
