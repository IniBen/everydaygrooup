<template>

    <!-- Section 1 -->
    <section class="py-80 bg-vvv h-full">
        <div class="px-10 mx-auto max-w-7xl">
            <div class="flex flex-wrap items-center justify-center">
                <div class="max-w-sm mb-16 lg:mb-0 lg:max-w-2xl lg:w-1/2 lg:px-4">
                    <h2 class="mb-4 text-2xl font-bold tracking-tight text-blue-900 lg:text-3xl xl:text-4xl">Send us a message.</h2>
                    <p class="mb-8 leading-loose text-gray-500">Get in touch with Live Assured to get <br> real time answers to your questions</p>
                </div>
                <div class="w-full px-4 lg:w-1/2">
                    <div class="max-w-sm mx-auto lg:mr-0 lg:ml-auto">
                        <div class="overflow-hidden bg-white rounded-md shadow-sm w-full">
                            <div class="px-6 py-8">
                                <form onsubmit="event.preventDefault();">
                                    <div class="flex flex-wrap mb-4 -mx-2">
                                        <div class="w-full px-2 mb-4 lg:mb-0 lg:w-1/2">
                                            <label for="First Name" class="mb-2 font-medium text-gray-500 peer-focus:text-blue-600 text-start">First Name<span class="text-red-500">*</span></label>
                                            <input class="py-2.5 px-4 w-full bg-white border focus:ring-2 focus:ring-opacity-90 focus:ring-indigo-500 border-gray-100 rounded-xl focus:outline-none hover:outline-blue-900 w-72" type="text">
                                        </div>
                                        <div class="w-full px-2 lg:w-1/2">
                                            <label for="Last Name" class="mb-2 font-medium text-gray-500 peer-focus:text-blue-600 text-start">Last Name<span class="text-red-500">*</span></label>
                                            <input class="py-2.5 px-4 w-full bg-white border focus:ring-2 focus:ring-opacity-90 hover:outline-blue-900 focus:ring-indigo-500 border-gray-100 rounded-xl focus:outline-none w-72" type="text">
                                        </div>
                                    </div>
                                    <label for="email" class="mb-2 font-medium text-gray-500 peer-focus:text-blue-600 text-start">Email <span class="text-red-500">*</span></label>
                                    <input class="py-2.5 px-4 mb-4 w-full bg-white border focus:ring-2 focus:ring-opacity-90 hover:outline-blue-900 focus:ring-indigo-500 border-gray-100 rounded-xl focus:outline-none" type="email">
                                    <label for="message" class="mb-2 font-medium text-gray-500 peer-focus:text-blue-600 text-start">Message<span class="text-red-500">*</span></label>
                                    <textarea class="block w-full bg-white py-4 px-6 mb-2 resize-none  hover:outline-blue-900 text-sm text-gray-500" name="" id="" rows="4"></textarea>
                                    <button class="w-full py-3 mb-4 font-bold text-white bg-indigo-600 rounded-xl hover:bg-indigo-500">Sign Up</button>
                                </form>
                                <p class="text-xs text-gray-400">
                                    <span>Already have an account?</span>
                                    <a class="text-indigo-500" href="#">Sign In</a>
                                </p>
                            </div>
                            <div class="py-2 text-xs font-medium text-gray-300 border-t border-gray-100 bg-gray-50">By signing up, you agree to our <a href="#_" class="text-indigo-400 underline">Terms of Service</a></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

</template>

<script>
export default {};
</script>

<style>
    .bg-vvv{
        background-image: url(~/assets/Rectangle.png);
        height: 100%;
    }
</style>