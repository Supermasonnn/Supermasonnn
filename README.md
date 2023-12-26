<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aero Tech</title>
    <style>
        body {
            background-color: white;
            color: black;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: red;
            padding: 10px;
            text-align: center;
        }

        main {
            padding: 20px;
        }

        .product-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-top: 20px;
            border: 1px solid #ddd;
            padding: 15px;
        }

        .product-image img {
            width: 200px;
            height: 200px;
        }

        .product-details {
            flex-grow: 1;
            margin-left: 20px;
        }

        .buy-now-button {
            background-color: red;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            text-decoration: none;
            display: inline-block;
            text-align: center;
            line-height: 2;
        }
    </style>
</head>
<body>
    <header>
        <h1>Aero Tech</h1>
    </header>

    <main>
        <section class="product-container">
            <div class="product-image">
                <img src="https://cdn.discordapp.com/attachments/1109756925802971257/1188203383945961542/20231223_193420_0000.png?ex=6599aba2&is=658736a2&hm=933a979b720caffcf12ff0eee1f531684a23348389ca35e998c479df52905b07" alt="Product Image">
            </div>
            <div class="product-details">
                <h2>Robux</h2>
                <p> Airport standard desk. ( make a discord ticket to get your product.)</p>
                <p><strong>Price:</strong> 20 Robux</p>
                <a href="https://www.roblox.com/game-pass/676197711" target="_blank" class="buy-now-button">Buy Now</a>
            </div>
        </section>
    </main>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Socials</title>
    <style>
        /* Your existing styles here */

        /* Modal styles */
        .overlay {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
            justify-content: center;
            align-items: center;
        }

        .modal {
            background: white;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
        }

        .close-button {
            cursor: pointer;
            background-color: red;
            color: white;
            padding: 10px 20px;
            border: none;
            text-decoration: none;
            display: inline-block;
            text-align: center;
            line-height: 2;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Socials</h1>
    </header>

    <main>
        <!-- Add a button to trigger the modal with the Discord logo -->
        <button onclick="openModal()">
            <img src="https://cdn.discordapp.com/attachments/1113508097646927892/1188540762917453917/IMG_3434.png?ex=659ae5d7&is=658870d7&hm=a5fc97ab65b91447a0aca61fc6a636cbe3c01f8c9c45b3708c481c3f1a0e43e7&" alt="Discord Logo" width="50" height="50">
        </button>

        <!-- Product section -->
        <section class="product-container">
            <!-- Your existing product content here -->
        </section>

        <!-- Modal overlay -->
        <div id="overlay" class="overlay">
            <!-- Modal content -->
            <div class="modal">
                <!-- Content of your Discord message -->
                <p>Join our Discord for the latest updates and support!</p>

                <!-- Discord link -->
                <a href="https://discord.com/invite/BHYz7E2Z" target="_blank" class="close-button">Join Discord</a>

                <!-- Close button -->
                <button class="close-button" onclick="closeModal()">Close</button>
            </div>
        </div>
    </main>

    <script>
        // JavaScript functions to open and close the modal
        function openModal() {
            document.getElementById("overlay").style.display = "flex";
        }

        function closeModal() {
            document.getElementById("overlay").style.display = "none";
        }
    </script>
</body>
</html>
