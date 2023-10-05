# Test
My portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ticket Purchase Platform</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        .ticket {
            border: 1px solid #ccc;
            padding: 10px;
            margin-bottom: 10px;
            display: flex;
            justify-content: space-between;
        }
        .ticket .details {
            flex-grow: 1;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ticket Purchase Platform</h1>
    </header>
    <div class="container">
        <h2>Available Tickets</h2>
        <div class="ticket">
            <div class="details">
                <h3>Event Name 1</h3>
                <p>Date: October 10, 2023</p>
                <p>Price: $50.00</p>
            </div>
            <button class="buy-button" onclick="buyTicket(1)">Buy</button>
        </div>
        <div class="ticket">
            <div class="details">
                <h3>Event Name 2</h3>
                <p>Date: November 15, 2023</p>
                <p>Price: $40.00</p>
            </div>
            <button class="buy-button" onclick="buyTicket(2)">Buy</button>
        </div>
        <!-- Add more ticket listings here -->
    </div>
    <script>
        function buyTicket(eventId) {
            // In a real platform, this function would handle the purchase logic.
            alert(`You have purchased a ticket for Event ${eventId}`);
        }
    </script>
</body>
</html>
