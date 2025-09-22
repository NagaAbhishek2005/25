:root {
    --main-colour:red;
    --secondary-colour: lightgray;
}
.container {
    width: 100%;
    margin: 0 auto;
    padding: 20px;
    background-color: var(--secondary-colour);
    border-radius: 20px;
}
.main-heading {
    font-family: Arial, sans-serif;
    font-size: 2rem;
    font-weight: bold;
    font-style: italic;
    text-align: center;
    color: var(--main-color);
    text-decoration: underline;
    line-height: 1.5;
}
.text-section {
    margin-bottom: 30px;
}
.text-demo {
    font-variant: small-caps;
    letter-spacing: 2px;
    word-spacing: 4px;
    white-space: nowrap;
    text-overflow: ellipsis;
    overflow: hidden;
    max-width: 200px;
}
.text-shadow{
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.90);
}
.text-transform{
    text-transform: uppercase;
    text-indent: 20px;
    hyphens: auto;
}
