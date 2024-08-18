<template>
    <div class="contacts" id="contacts">
        <div class="cont-text"><h1>Contact</h1></div>
        <div class="form">
            <form action="">
                <div class="input-label">
                    <h1>Name</h1>
                    <input class="input" type="text" name="name" id="">
                </div>
                <div class="input-label">
                    <h1>Email</h1>
                    <input class="input" type="email" name="name" id="">
                </div>
                <div class="input-label">
                    <h1>Content</h1>
                    <textarea class="input" name="content" id="" rows="15" cols="110" placeholder="Insira aqui seu texto!"></textarea>
                </div>
                <input type="submit" class="submit-btn" value="Submit">
            </form>
        </div>
    </div>
</template>

<style>
    .cont-text {
        display: flex;
        align-items: center;
        justify-content: center;
        height: 220px;
    }
    .cont-text > h1 {
        font-size: 64px;
        margin: 0;
    }
    .form {
        background-color: #FF7A46;
        display: flex;
        align-items: center;
        justify-content: center;
        height: 600px;
    }
    .form > form {
        display: flex;
        flex-direction: column;
        gap: 12px;
    }
    .input-label {
        display: flex;
        flex-direction: column;
    }
    .input-label h1 {
        color: white;
    }
    .input-label input,
    .input-label textarea {
        width: 100%;
        padding: 10px;
        border: none;
        border-radius: 4px;
        box-sizing: border-box;
    }
    .input-label textarea {
        resize: vertical;
    }
    .submit-btn {
        color: black;
        width: 35%;
        font-size: 32px;
        font-weight: bold;
        align-self: center;
        padding: 12px 20px;
        border: none;
        background-color: #FFC260        ;
        border-radius: 4px;
        font-size: 16px;
        cursor: pointer;
        margin-top: 12px;
    }
</style>