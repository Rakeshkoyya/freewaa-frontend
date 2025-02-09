<template>
    <!-- Contact section start -->
	<section id="contact-section" class="px-12 lg:px-32 py-16 relative">
        <!-- Main text start -->
		<h1 class="uppercase text-5xl mb-4 font-semibold ">
			Contact us
		</h1>
		<!-- Main text end -->
        

        <!-- Form start -->
        <div class="grid grid-cols-1 md:grid-cols-2 w-full">
            <div class="hidden md:flex justify-center items-center">
                <img src="@/assets/bottlesrm.png" alt="">
            </div>
            
            <section class="contact-section">
                <h2 class="text-2xl font-bold mb-4">Ready to make a splash with your brand? We'd love to hear from you!</h2>
                <div class="contact-info">
                <p>Email: <a href="mailto:contact.freewaa@gmail.com" class="text-blue-500 hover:underline">contact.freewaa@gmail.com</a></p>
                <p>Phone: <a href="tel:+916304806787" class="text-blue-500 hover:underline">+91 6304806787</a> | <a href="tel:+919030595999" class="text-blue-500 hover:underline">+91 9030595999</a></p>
                <!-- <p>Address: <span>Your Company Address</span></p> -->
                </div>
                <p class="mt-4">Or simply fill out our contact form below, and one of our creative strategists will be in touch to discuss how we can transform your brand's presence with the power of free water.</p>
                <p class="mt-2 font-medium">Let's start a conversation—because when it comes to building trust, every drop counts.</p>
             
                <button @click="openFormLink" class="mt-6 px-4 py-2 btn">
                    Contact us
                </button>
            </section>

            <!-- <div class="flex flex-col w-full items-center">
                <label for="user_email" class="text-stone-500 text-left">E-mail address</label>
                <input type="email" name="user_email" id="user_email" class="bg-stone-200 py-2 px-4 w-full mb-6 xl:w-1/2">

                <label for="user_message" class="text-stone-500 text-left">Message</label>
                <textarea name="user_message" id="user_message" cols="30" rows="10" class="bg-stone-200 py-2 px-4 w-full mb-6 xl:w-1/2"></textarea>

                <button class="btn w-full md:w-1/2">Send</button>
            </div> -->


        </div>
        <!-- Form end -->

        <!-- Circle start -->
        <div class="bg-neutral-200 h-44 w-44 md:h-52 md:w-52 rounded-full absolute -top-20 left-0 mt-16 -z-20"></div>
        <!-- Circle end -->
	</section>
	<!-- Contact section end -->
</template>

<script>
export default {
    methods: {
    openFormLink() {
		  window.open("https://forms.gle/tGuBxHzhxs5T4UHu5", "_blank");
		}
    }
}
</script>

<style scoped>

.contact-section {
  padding: 1.5rem;
  background-color: #f9f9f9;
  border-radius: 12px;
  max-width: 600px;
  margin: 2rem auto;
}
.contact-info p {
  margin: 0.5rem 0;
}

</style>