body {
    margin: 0;
    padding: 0;
}

.page {
    position: relative;
    width: 100%;
    height: 100vh;
    background-color: aqua;
}

.bg-image {
    position: absolute;
    inset: 0;
    background-image: url("/home/mayfaria/Downloads/Criar-web-site-profissional.jpeg");
    background-size: cover;
    background-position: center;
    opacity: 0.4;
    z-index: 1;
}

.content {
    position: relative;
    z-index: 2;
    height: 100%;
    display: flex;
    flex-direction: column; /* texto acima dos botões */
    justify-content: center;
    align-items: center;
    gap: 40px;
}

/* Texto */
.text-area {
    text-align: center;
    font-family: 'Courier New', Courier, monospace;
}

.text-area h1 {
    margin: 0;
    font-size: 48px;
}

.text-area p {
    margin: 5px 0 0;
    font-size: 18px;
}

.buttons {
    display: flex;
    gap: 300px;
}

.btn {
    font-family: 'Courier New', Courier, monospace;
    font-size: 18px;
    padding: 15px 40px;
    background-color: white;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    transition: 0.3s;
}

.btn:hover {
    background-color: #0044cc;
    color: white;
    transform: scale(1.05);
}
