<template>
    <form class="contact-form">
        <div class="form-group">
            <label for="msg-name">Email</label>
            <input type="text" id="msg-name" class="form-control">
        </div>
        <div class="form-group">
            <label for="msg-email">Name</label>
            <input type="text" id="msg-email" class="form-control">
        </div>
        <div class="form-group">
            <label for="msg-content">Message</label>
            <textarea rows="10" id="msg-content" class="form-control"></textarea>
        </div>
        <div class="form-group">
            <button class="btn">Send</button>
        </div>
    </form>
</template>

<script>
    export default {
        name: 'ContactForm',
    }
</script>

<style scoped>
    .contact-form {
        width: 360px;
    }

    .form-group {
        padding: 10px;
    }

    .form-control {
        width: 100%;
        padding: 12px 15px;
        border: 1px solid #ccc;
        border-radius: 4px;
        box-sizing: border-box;
    }

    input[type=text].form-control {
        margin: 8px 0;
        display: inline-block;
    }

    textarea.form-control {
        resize: none;
    }

    .btn {
        padding: 8px 10px;
        outline: none;
        border: none;
        background: #00b710;
        font-size: 16px;
        width: 100%;
        border-radius: 4px;
        text-align: center;
    }
</style>
