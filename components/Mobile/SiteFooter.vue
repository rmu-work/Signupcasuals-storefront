<template>
  <footer class="bg-footer w-full px-4 pt-10">
    <div class="flex flex-col gap-10">
      <div class="text-sm text-head flex flex-col gap-4">
        <div class="col-span-3">
          <img src="~/assets/images/logo.png" class="block h-14" />
        </div>
        <p class="leading-5">
          SignUp Casuals, Ground floor,<br />
          City centre, Thrissur<br />
          Kerala-680001<br />
          India<br />
        </p>
        <p class="leading-5">
          support@signupcasuals.com<br />
          +91 9562889921
        </p>
      </div>
      <!--  -->
      <div class="flex">
        <div class="w-1/2">
          <h3 class="text-lg text-head font-medium mb-4">COMPANY</h3>
          <ul class="footer-links flex flex-col space-y-4 text-sm">
            <li><nuxt-link to="/about">About Us</nuxt-link></li>
              <li><nuxt-link to="/privacy-policy">Privacy Policy</nuxt-link></li>
              <li><nuxt-link to="/payments">Payments</nuxt-link></li>
              <li><nuxt-link to="/contact">Contact Us</nuxt-link></li>
          </ul>
        </div>
        <div class="w-1/2">
          <h3 class="text-lg text-head font-medium mb-4">SHOP</h3>
          <ul class="footer-links flex flex-col space-y-4 text-sm">
            <li><a href="#">New Arrivals</a></li>
            <li><a href="#">Men </a></li>
            <li><a href="#">Women </a></li>
            <li><a href="#">Shop All </a></li>
          </ul>
        </div>
      </div>
      <!--  -->
      <div>
        <h3 class="text-lg text-head font-medium mb-4">HELP</h3>
        <ul class="footer-links flex flex-col space-y-4 text-sm">
          <li><nuxt-link to="/terms-conditions">Terms & Conditions</nuxt-link></li>
              <li><nuxt-link to="/shipping-policy">Shipping Policy</nuxt-link></li>
              <li><nuxt-link to="/exchange-cancellation-policy">Exchange & Cancellation Policy</nuxt-link></li>
              <li><nuxt-link to="/return-refund-policy">Return & Refund Policy</nuxt-link></li>
        </ul>
      </div>
      <!--  -->
      <div class="flex flex-col gap-4">
        <h3 class="text-lg text-head font-medium">SUBSCRIBE</h3>
        <p class="text-sm leading-5">
          Be the first to get the latest news about trends, <br />
          promotions, and much more!
        </p>
        <div class="flex items-center gap-4 bg-white px-4 py-4 text-head">
          <input
            type="email"
            name=""
            id=""
            placeholder="Your email address"
            class="text-sm text-head flex-1"
          />
          <button class="font-medium uppercase">Join</button>
        </div>
        <h5 class="text-[15] text-head font-medium">Secure payments</h5>
        <img src="~/assets/images/payments.png" />
      </div>
      <!--  -->
      <div
        class="pt-4 pb-6 border-t border-[#CFCDCD] flex flex-col gap-4 text-sm"
      >
        <div>©SignUp Casuals  &nbsp; &nbsp;Powered by Knowbin Technologies Pvt Ltd</div>
        <div class="flex gap-4">
          <span class="text-second">Language</span>
          <span>United Kingdom | English</span>
        </div>
        <div class="flex gap-4">
          <span class="text-second">Currency</span>
          <span>&#8377; INR</span>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "MobileViewFooter",
};
</script>

<style>

</style>
