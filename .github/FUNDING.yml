<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flaming Thunder</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            text-align: center;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            max-width: 400px;
            margin: 50px auto;
        }
        .title {
            font-size: 30px;
            color: #d4af37; /* doré */
        }
        .price {
            color: #333;
            font-size: 22px;
            margin: 15px 0;
        }
        .button {
            margin-top: 15px;
            padding: 10px 20px;
            background-color: #d4af37; /* doré */
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 4px;
        }
        .button:hover {
            background-color: #b3942f;
        }
        .comment-section {
            margin-top: 20px;
            text-align: left;
        }
        .comment {
            padding: 5px;
            width: 100%;
            margin-top: 10px;
        }
        .comment-button {
            padding: 5px 10px;
            margin-top: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 4px;
        }
        .comment-button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="title">Flaming Thunder</h1>
        <p>En stock</p>
        <p class="price">4,50 €</p>
        <button class="button" onclick="addToCart()">Ajouter au panier</button>
        
        <div class="comment-section">
            <h3>Laissez un commentaire :</h3>
            <input type="text" id="commentInput" class="comment" placeholder="Commentez ici...">
            <button class="comment-button" onclick="submitComment()">Soumettre</button>
            <div id="commentsList"></div>
        </div>
    </div>

    <script>
        function addToCart() {
            alert("Produit ajouté au panier !");
        }

        function submitComment() {
            const commentInput = document.getElementById('commentInput');
            const comment = commentInput.value;
            if (comment.trim()) {
                const commentsList = document.getElementById('commentsList');
                const newComment = document.createElement('p');
                newComment.textContent = comment;
                commentsList.appendChild(newComment);
                commentInput.value = '';
            } else {
                alert("Veuillez entrer un commentaire !");
            }
        }
    </script>
</body>
</html>
