<template>
  <div class="w-full img-4">
    <div class="">
      <main class="h-screen">
        <div class="pt-24 px-2 sm:pl-20 sm:pr-8">
          <div class="flex">
            <div class="lg:w-2/5 space-y-20">
              <div class="">
                <h2 class="font-serif text-5xl hidden lg:block">Contact</h2>
              </div>

              <div class="lg:relative">
                <p class="font-serif text-2xl hidden lg:block">
                  Connect with me
                </p>
                <div
                  class="
                    flex flex-col
                    lg:flex-row
                    absolute
                    right-2
                    sm:right-4
                    lg:top-8 lg:left-0
                    gap-2
                  "
                >
                  <!-- social icons -->
                  <a href="#">
                    <img
                      src="https://img.icons8.com/wired/24/6e5494/github.png"
                    />
                  </a>

                  <a href="#">
                    <img
                      src="https://img.icons8.com/wired/24/0077b5/linkedin.png"
                    />
                  </a>

                  <a href="#">
                    <img
                      src="https://img.icons8.com/wired/24/4267B2/facebook.png"
                    />
                  </a>

                  <a href="#">
                    <img
                      src="https://img.icons8.com/wired/24/8a3ab9/instagram-new.png"
                    />
                  </a>

                  <a href="#">
                    <img
                      src="https://img.icons8.com/wired/24/00ACEE/twitter.png"
                    />
                  </a>

                  <a href="#">
                    <img
                      src="https://img.icons8.com/wired/24/4FCE5D/whatsapp.png"
                    />
                  </a>
                  <a href="#">
                    <img
                      src="https://img.icons8.com/wired/24/BB001B/gmail.png"
                    />
                  </a>
                </div>
              </div>

              <div class="space-y-12 hidden lg:block">
                <p>
                  <span class="font-serif text-lg">Email:</span>
                  <br />okmarq@gmail.com
                </p>
                <p>
                  <span class="font-serif text-lg">Phone:</span> <br />+234 (0)
                  810-725-0441
                </p>
              </div>
            </div>

            <div class="w-full space-y-4 sm:space-y-14 block">
              <div class="">
                <h3
                  class="font-serif text-2xl md:text-3xl font-semibold italic"
                >
                  Want to know more about me, build something awesome or
                  collaborate?
                </h3>
              </div>
              <div class="">
                <p class="text-secondary-main font-serif text-2xl">
                  Send me a message
                </p>
                <form class="flex flex-col gap-1 sm:gap-0 pr-8" action="">
                  <div
                    class="flex flex-col sm:flex-row gap-1 sm:gap-1 lg:gap-1"
                  >
                    <input
                      class="
                        flex-1
                        placeholder-white
                        bg-gray-300 bg-opacity-20
                        p-3
                        border-none
                        focus:outline-none focus:ring-0
                        rounded-t-lg
                        sm:rounded-tr-none
                      "
                      type="text"
                      name=""
                      placeholder="Your name (required)"
                      required
                    />

                    <input
                      class="
                        flex-1
                        placeholder-white
                        bg-gray-300 bg-opacity-20
                        p-3
                        border-none
                        focus:outline-none focus:ring-0
                        rounded-none
                        sm:rounded-tr-lg
                      "
                      type="email"
                      name=""
                      placeholder="Your email (required)"
                      required
                    />
                  </div>
                  <div class="flex">
                    <textarea
                      class="
                        flex-1
                        placeholder-white
                        bg-gray-300 bg-opacity-20
                        p-3
                        border-none
                        w-full
                        h-32
                        focus:outline-none focus:ring-0
                      "
                      name=""
                      placeholder="Your message (required)"
                      required
                    ></textarea>
                  </div>
                  <div class="">
                    <button
                      class="
                        p-3
                        rounded-b-lg
                        bg-secondary-main
                        font-serif
                        text-lg
                        w-full
                      "
                    >
                      Send Message
                    </button>
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
      </main>
    </div>
  </div>
</template>

<script>
export default {
  name: "Contact",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.img-4 {
  background-image: url("../assets/images/patterns/world.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
