<script setup></script>

<template>
    <div class="contact_container">
        <h1>Contact Us</h1>
        <div class="contact_content">
            <div class="contact_infor">
                <p>sherlockwayne233@gmail.com</p>
                <p>+254 715 138 424</p>
            </div>
            <div class="contact_form">
                <form action="" method="post">
                   <div class="form_infor">
                    <input type="text" id="names" name="name" placeholder="Enter you Names">
                    <input type="email" name="email" id="email" placeholder="Enter Your Email Address">
                    <textarea name="message" id="message" cols="10" rows="7" placeholder="Write Your message here"></textarea>
                   </div>
                   <div class="btn">
                        <a href="mailto:sherlockwayne233@gmail.com">
                            <button type="submit">Submit</button>
                        </a>
                   </div>
                </form>
            </div>
        </div>
    </div>
</template>