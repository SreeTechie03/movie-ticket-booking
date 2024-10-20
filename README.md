# Movie Ticket Booking and Confirmation

This project provides an online movie ticket booking system, which includes a booking interface and ticket confirmation page. The main components are HTML files with embedded JavaScript and CSS for functionality and styling.

## Files

1. **Movie Ticket Booking.html**: 
   - This page allows users to book movie tickets by selecting a movie, date, time, and venue.
   - It stores the booking details using the browser's `localStorage`.

2. **Ticket Booking.html**: 
   - Similar to the main booking page, it provides a user-friendly interface for booking tickets and saving the data.

3. **Ticket Confirmation.html**: 
   - This page confirms the user's ticket booking.
   - It retrieves the movie details from `localStorage` and displays them in a confirmation message.
   - The "Proceed" button redirects the user to the next page (which can be customized).

4. **large.png**: 
   - A small icon resembling a popcorn container with the text "2024" is included, possibly used in the confirmation page as a background or icon.

## How It Works

### Booking Process:
1. The user books a ticket by entering movie details (name, date, time, and venue).
2. These details are stored in `localStorage`.

### Confirmation Process:
1. The confirmation page (`Ticket Confirmation.html`) retrieves the booking details from `localStorage`.
2. The user can see the confirmed details such as movie name, date, time, and venue.
3. The "Proceed" button allows the user to move to the next page for further actions.

## Customization

- **Images**: 
   You can replace `large.png` with a different icon by updating the image source in the confirmation page's CSS background property.
- **Proceed Button**: 
   The "Proceed" button on the confirmation page redirects to `nextPage.html`. Update this URL to your desired target page in the script section of `Ticket Confirmation.html`.

## Instructions

1. Open `Movie Ticket Booking.html` or `Ticket Booking.html` in a browser to start booking tickets.
2. After submitting the booking, open `Ticket Confirmation.html` to view the ticket confirmation.
3. Click "Proceed" to move to the next step in the process.

## Future Improvements

- Add server-side functionality to handle booking storage and retrieval.
- Integrate payment processing and seat selection.
