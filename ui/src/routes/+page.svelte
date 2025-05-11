<main>
    <!-- Hero Section -->
    <section class="flex flex-col items-center justify-center gap-8 m-6">
        <div class="space-y-6 max-w-2xl text-center">
            <h1 class="text-4xl font-bold font-baloo text-primary leading-tight ">
                Bringing local businesses together to share the cost of marketing.
            </h1>
            <p class="text-xl text-gray-700">
                Need more leads for your local business?
            </p>
            <div class="flex justify-center">
                <a href="#contact-section" class="daisy-btn daisy-btn-secondary daisy-btn-lg">
                    Contact Heath!
                </a>
            </div>
        </div>

        <div class="daisy-carousel w-full max-w-[1152px] max-h-[864px] shadow-2xl mt-4">
            <div id="item1" class="daisy-carousel-item w-full scroll-mt-[500px]">
                <img
                        src="/postcards-archive/february-1.png"
                        alt="February Postcard-Front"
                        class="w-full" />
            </div>
            <div id="item2" class="daisy-carousel-item w-full scroll-mt-[500px]">
                <img
                        src="/postcards-archive/february-2.png"
                        alt="February Postcard-Back"
                        class="w-full" />
            </div>
            <div id="item3" class="daisy-carousel-item w-full scroll-mt-[500px]">
                <img
                        src="/postcards-archive/march-1.png"
                        alt="March Postcard-Front"
                        class="w-full" />
            </div>
            <div id="item4" class="daisy-carousel-item w-full scroll-mt-[500px]">
                <img
                        src="/postcards-archive/march-2.png"
                        alt="March Postcard-Back"
                        class="w-full" />
            </div>
        </div>
        <div class="flex w-full justify-center gap-2 mb-4">
            <a href="#item1" class="daisy-btn daisy-btn-sm daisy-btn-secondary">1</a>
            <a href="#item2" class="daisy-btn daisy-btn-sm daisy-btn-secondary">2</a>
            <a href="#item3" class="daisy-btn daisy-btn-sm daisy-btn-secondary">3</a>
            <a href="#item4" class="daisy-btn daisy-btn-sm daisy-btn-secondary">4</a>
        </div>
    </section>


    <!-- Value Proposition Section -->
    <section class="relative">
        <div class="absolute inset-0 bg-[url(/conway-drone-shot.jpg)] w-full bg-center bg-contain bg-fixed"></div>
        <div class="absolute inset-0 bg-black/60"></div>

        <!-- Text overlay -->
        <div class="flex flex-col py-24 px-8 text-center">
            <h2 class="text-4xl font-bold font-baloo text-primary mb-2 drop-shadow-lg">Get Noticed!</h2>
            <p class="text-xl text-white drop-shadow-lg">Join this huge postcard mailed to roughly 10,000 residents in your city!</p>
        </div>
    </section>


    <!-- Postcard Graphic -->
    <section class="flex flex-auto justify-center m-8">
        <figure>
            <img
                src="marketing-postcard-graphic.png"
                alt="Preview of marketing postcard design"
                class="w-full max-w-[1152px] max-h-[864px]"
            />
        </figure>
    </section>


    <!-- Pricing Section -->
    <section>
        <h2 class="flex justify-center font-bold font-baloo text-3xl text-primary py-8">Pricing Options</h2>
        <ul class="flex flex-wrap justify-center"><!-- inches to pixels conversion is done with 96 PPI (pixels per inch) which is considered the standard conversion rate. It's as close as we can get -->
            <div class="overflow-x-auto max-w-full">
                <li class="daisy-card bg-accent w-[540px] h-[360px] m-2"><!-- width=5.625 inches aka 540 pixels --> <!-- height=3.75 inches aka 360 pixels -->
                    <div class="daisy-card-body">
                        <h2 class="daisy-card-title text-4xl text-base-100 justify-center">Large Ad: $800</h2>
                        <p class="flex text-neutral justify-center">Actual size!</p>
                    </div>
                </li>
            </div>
            <div class="flex flex-wrap justify-center">
                <li class="daisy-card bg-accent w-[264px] h-[360px] m-2"><!-- width=2.75 inches aka 264 pixels --> <!-- height=3.75 inches aka 360 pixels -->
                    <div class="daisy-card-body">
                        <h2 class="daisy-card-title text-2xl text-base-100 justify-center">Medium Ad: $500</h2>
                        <p class="flex text-neutral justify-center">Actual size!</p>
                    </div>
                </li>
                <li class="daisy-card bg-accent w-[264px] h-[174px] m-2"><!-- width=2.75 inches aka 264 pixels --> <!-- height=1.8125 inches aka 174 pixels -->
                    <div class="daisy-card-body ">
                        <h2 class="daisy-card-title text-xl text-base-100 justify-center">Small Ad: $300</h2>
                        <p class="text-neutral flex justify-center">Actual size!</p>
                    </div>
                </li>
            </div>
        </ul>
    </section>


    <!-- Contact Section -->
    <h2 class="flex justify-center font-bold font-baloo text-3xl py-8 text-primary">Contact Me Now!</h2>
    <section id="contact-section" class="flex justify-center gap-4 max-w-full">
        <div class="flex flex-col justify-center">
            <address class="text-center  font-bold">
                <p class="text-center font-bold text-accent">Call / Text</p>
                <a class="text-2xl" href="tel:5012877584">501.287.7584</a>

                <div class="daisy-divider">OR</div>

                <p class="text-center font-bold text-accent">Email</p>
                <a class="text-xl" href="mailto:besowshekheath@gmail.com">besowshekheath@gmail.com</a>
            </address>
        </div>
    </section>

    <!-- About Section -->
    <h2 class="flex text-primary font-bold font-baloo text-3xl justify-center m-8">About the Owner</h2>
    <section class="flex flex-wrap items-center justify-center gap-6 m-6">
        <figure>
            <img
                src="heath-headshot.jpeg"
                alt="Headshot of Heath, the owner"
                class="w-auto h-96"
            />
        </figure>
        <article class="w-lg">
            <p class="text-lg">Hi there, my name is Heath! As a small business owner myself, I LOVE seeing small businesses thrive and flourish. Marketing is such a crucial part of this success, but can be so costly! The postcard I put together here at Arkansas Profit Printing offers small businesses the opportunity to market themselves to the community in such a big way, but for a significantly lower cost. By each business contributing to the cost of the postcard, everyone gains exposure and saves money. It's a win-win! I look forward to working with you. Please do not hesitate to reach out with any questions!</p>
            <footer><br>
                <p class="text-lg">- Heath</p>
            </footer>
        </article>
    </section>
</main>