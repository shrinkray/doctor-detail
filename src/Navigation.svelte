
<!-- This example requires Tailwind CSS v2.0+ -->
<nav class="bg-white shadow">
  <div class="max-w-7xl mx-auto pb-2 px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between h-16">
      <div class="flex">
        <div class="-ml-2 mr-2 flex items-center md:hidden">
          <!-- Mobile menu button -->
          <button type="button" class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-indigo-500" aria-controls="mobile-menu" aria-expanded="false">
            <span class="sr-only">Open main menu</span>
  
            <svg aria-hidden="true" focusable="false" data-prefix="fal" data-icon="sparkles" class="w-6 h-6" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="fill-pink-500" d="M328.84 109.75l48.57 24.32 24.28 48.63a16 16 0 0 0 28.62 0l24.28-48.63 48.57-24.32a16 16 0 0 0 0-28.66l-48.57-24.32-24.28-48.63c-5.43-10.85-23.19-10.85-28.62 0l-24.28 48.63-48.57 24.32a16 16 0 0 0 0 28.66zM396.5 83a16.1 16.1 0 0 0 7.16-7.16L416 51.14l12.34 24.74A16.1 16.1 0 0 0 435.5 83l24.72 12.38-24.72 12.42a16.2 16.2 0 0 0-7.16 7.16L416 139.7 403.66 115a16.2 16.2 0 0 0-7.16-7.16l-24.72-12.42zm106.66 318.53l-48.57-24.31-24.28-48.63c-5.43-10.86-23.19-10.86-28.62 0l-24.28 48.63-48.57 24.31a16 16 0 0 0 0 28.67l48.57 24.31 24.28 48.63a16 16 0 0 0 28.62 0l24.28-48.63 48.57-24.31a16 16 0 0 0 0-28.67zm-67.66 26.71a16.17 16.17 0 0 0-7.16 7.17L416 460.15l-12.34-24.74a16.17 16.17 0 0 0-7.16-7.17l-24.72-12.37 24.72-12.38a16.17 16.17 0 0 0 7.16-7.17L416 371.59l12.34 24.73a16.17 16.17 0 0 0 7.16 7.17l24.72 12.38zM384 255.64a16.06 16.06 0 0 0-8.84-14.33L262.59 185 206.31 72.23c-5.43-10.86-23.19-10.86-28.62 0L121.41 185 8.84 241.31a16 16 0 0 0 0 28.67l112.57 56.36 56.28 112.71a16 16 0 0 0 28.62 0l56.28-112.71L375.16 270a16.09 16.09 0 0 0 8.84-14.36zm-140.5 44.43a16.1 16.1 0 0 0-7.16 7.16L192 396.06l-44.34-88.83a16.1 16.1 0 0 0-7.16-7.16l-88.72-44.43 88.72-44.42a16.2 16.2 0 0 0 7.16-7.16L192 115.23l44.34 88.83a16.2 16.2 0 0 0 7.16 7.16l88.72 44.42z"></path></svg>
            <svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="car" class="w-6 h-6" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="fill-pink-500" d="M499.99 176h-59.87l-16.64-41.6C406.38 91.63 365.57 64 319.5 64h-127c-46.06 0-86.88 27.63-103.99 70.4L71.87 176H12.01C4.2 176-1.53 183.34.37 190.91l6 24C7.7 220.25 12.5 224 18.01 224h20.07C24.65 235.73 16 252.78 16 272v48c0 16.12 6.16 30.67 16 41.93V416c0 17.67 14.33 32 32 32h32c17.67 0 32-14.33 32-32v-32h256v32c0 17.67 14.33 32 32 32h32c17.67 0 32-14.33 32-32v-54.07c9.84-11.25 16-25.8 16-41.93v-48c0-19.22-8.65-36.27-22.07-48H494c5.51 0 10.31-3.75 11.64-9.09l6-24c1.89-7.57-3.84-14.91-11.65-14.91zm-352.06-17.83c7.29-18.22 24.94-30.17 44.57-30.17h127c19.63 0 37.28 11.95 44.57 30.17L384 208H128l19.93-49.83zM96 319.8c-19.2 0-32-12.76-32-31.9S76.8 256 96 256s48 28.71 48 47.85-28.8 15.95-48 15.95zm320 0c-19.2 0-48 3.19-48-15.95S396.8 256 416 256s32 12.76 32 31.9-12.8 31.9-32 31.9z"></path></svg>

          </button>
        </div>
        <div class="flex-shrink-0 flex items-center">
          <svg aria-hidden="true" focusable="false" data-prefix="fal" data-icon="sparkles" class="hidden sm:block w-6 h-6" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="svelte" d="M328.84 109.75l48.57 24.32 24.28 48.63a16 16 0 0 0 28.62 0l24.28-48.63 48.57-24.32a16 16 0 0 0 0-28.66l-48.57-24.32-24.28-48.63c-5.43-10.85-23.19-10.85-28.62 0l-24.28 48.63-48.57 24.32a16 16 0 0 0 0 28.66zM396.5 83a16.1 16.1 0 0 0 7.16-7.16L416 51.14l12.34 24.74A16.1 16.1 0 0 0 435.5 83l24.72 12.38-24.72 12.42a16.2 16.2 0 0 0-7.16 7.16L416 139.7 403.66 115a16.2 16.2 0 0 0-7.16-7.16l-24.72-12.42zm106.66 318.53l-48.57-24.31-24.28-48.63c-5.43-10.86-23.19-10.86-28.62 0l-24.28 48.63-48.57 24.31a16 16 0 0 0 0 28.67l48.57 24.31 24.28 48.63a16 16 0 0 0 28.62 0l24.28-48.63 48.57-24.31a16 16 0 0 0 0-28.67zm-67.66 26.71a16.17 16.17 0 0 0-7.16 7.17L416 460.15l-12.34-24.74a16.17 16.17 0 0 0-7.16-7.17l-24.72-12.37 24.72-12.38a16.17 16.17 0 0 0 7.16-7.17L416 371.59l12.34 24.73a16.17 16.17 0 0 0 7.16 7.17l24.72 12.38zM384 255.64a16.06 16.06 0 0 0-8.84-14.33L262.59 185 206.31 72.23c-5.43-10.86-23.19-10.86-28.62 0L121.41 185 8.84 241.31a16 16 0 0 0 0 28.67l112.57 56.36 56.28 112.71a16 16 0 0 0 28.62 0l56.28-112.71L375.16 270a16.09 16.09 0 0 0 8.84-14.36zm-140.5 44.43a16.1 16.1 0 0 0-7.16 7.16L192 396.06l-44.34-88.83a16.1 16.1 0 0 0-7.16-7.16l-88.72-44.43 88.72-44.42a16.2 16.2 0 0 0 7.16-7.16L192 115.23l44.34 88.83a16.2 16.2 0 0 0 7.16 7.16l88.72 44.42z"></path></svg>
            <svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="car" class="hidden sm:block w-6 h-6" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="svelte" d="M499.99 176h-59.87l-16.64-41.6C406.38 91.63 365.57 64 319.5 64h-127c-46.06 0-86.88 27.63-103.99 70.4L71.87 176H12.01C4.2 176-1.53 183.34.37 190.91l6 24C7.7 220.25 12.5 224 18.01 224h20.07C24.65 235.73 16 252.78 16 272v48c0 16.12 6.16 30.67 16 41.93V416c0 17.67 14.33 32 32 32h32c17.67 0 32-14.33 32-32v-32h256v32c0 17.67 14.33 32 32 32h32c17.67 0 32-14.33 32-32v-54.07c9.84-11.25 16-25.8 16-41.93v-48c0-19.22-8.65-36.27-22.07-48H494c5.51 0 10.31-3.75 11.64-9.09l6-24c1.89-7.57-3.84-14.91-11.65-14.91zm-352.06-17.83c7.29-18.22 24.94-30.17 44.57-30.17h127c19.63 0 37.28 11.95 44.57 30.17L384 208H128l19.93-49.83zM96 319.8c-19.2 0-32-12.76-32-31.9S76.8 256 96 256s48 28.71 48 47.85-28.8 15.95-48 15.95zm320 0c-19.2 0-48 3.19-48-15.95S396.8 256 416 256s32 12.76 32 31.9-12.8 31.9-32 31.9z"></path></svg>        </div>
        <div class="hidden md:ml-6 md:flex md:space-x-8">
          <!-- Current: "border-indigo-500 text-gray-900", Default: "border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700" -->
          <a href="#" class="border-indigo-500 text-gray-900 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">
            The Garage
          </a>
          <a href="#" class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">
            Our Prices
          </a>
          <a href="#" class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">
            Services
          </a>
        </div>
      </div>
      <div class="flex items-center">
        <div class="flex-shrink-0">
          <button type="button" class="relative inline-flex items-center px-4 py-2 border border-transparent text-sm font-medium rounded-md text-white bg-indigo-600 shadow-sm hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500">
            <!-- Heroicon name: solid/plus-sm -->
            <svg aria-hidden="true" focusable="false" data-prefix="far" data-icon="calendar-plus" class="w-5 h-5 mr-2 -ml-1" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><path fill="currentColor" d="M336 292v24c0 6.6-5.4 12-12 12h-76v76c0 6.6-5.4 12-12 12h-24c-6.6 0-12-5.4-12-12v-76h-76c-6.6 0-12-5.4-12-12v-24c0-6.6 5.4-12 12-12h76v-76c0-6.6 5.4-12 12-12h24c6.6 0 12 5.4 12 12v76h76c6.6 0 12 5.4 12 12zm112-180v352c0 26.5-21.5 48-48 48H48c-26.5 0-48-21.5-48-48V112c0-26.5 21.5-48 48-48h48V12c0-6.6 5.4-12 12-12h40c6.6 0 12 5.4 12 12v52h128V12c0-6.6 5.4-12 12-12h40c6.6 0 12 5.4 12 12v52h48c26.5 0 48 21.5 48 48zm-48 346V160H48v298c0 3.3 2.7 6 6 6h340c3.3 0 6-2.7 6-6z"></path></svg>
            <span>Schedule a Visit</span>
          </button>
        </div>
      </div>
    </div>
  </div>
    
    <!-- Mobile menu, show/hide based on menu state. -->
  <div class="md:hidden" id="mobile-menu">
    <div class="pt-2 pb-3 space-y-1">
      <!-- Current: "bg-indigo-50 border-indigo-500 text-indigo-700", Default: "border-transparent text-gray-500 hover:bg-gray-50 hover:border-gray-300 hover:text-gray-700" -->
      <a href="#" class="bg-indigo-50 border-indigo-500 text-indigo-700 block pl-3 pr-4 py-2 border-l-4 text-base font-medium sm:pl-5 sm:pr-6">The Garage</a>
      <a href="#" class="border-transparent text-gray-500 hover:bg-gray-50 hover:border-gray-300 hover:text-gray-700 block pl-3 pr-4 py-2 border-l-4 text-base font-medium sm:pl-5 sm:pr-6">Our Prices</a>
      <a href="#" class="border-transparent text-gray-500 hover:bg-gray-50 hover:border-gray-300 hover:text-gray-700 block pl-3 pr-4 py-2 border-l-4 text-base font-medium sm:pl-5 sm:pr-6">Services</a>
      
    </div>
  </div>
</nav>
