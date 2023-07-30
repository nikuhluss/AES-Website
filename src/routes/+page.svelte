<!-- Wrap the entire content in a single container -->
<div class="container grid grid-cols-1 m-auto h-screen">
    <!-- Navbar -->
    <div class="grid grid-cols-1 md:grid-cols-2 gap-2 md:mt-auto md:mb-4"> <!-- Use md:grid-cols-2 to set 2 columns on desktop -->
        <div class="flex mt-4 md:my-0 md:ml-2 md:mr-6 md:bg-transparent justify-center md:justify-start"> <!-- Use md: to apply styles only on desktop -->
            <h1 class="text-4xl cursor-default">
                Amanda E. Scott
            </h1>
        </div>
        <div class="flex md:flex items-center justify-center mb-3 md:my-4"> <!-- Use md: to apply flex styles only on desktop -->
            <ul class="flex justify-center md:text-sm">
                <li class="mr-2">
                    <a class="hover:text-blue-800" href="#">About</a>
                </li>
                <p class="cursor-default">|</p>
                <li class="mx-2">
                    <a class="hover:text-blue-800" href="#">Writing</a>
                </li>
                <p class="cursor-default">|</p>
                <li class="mx-2">
                    <a class="hover:text-blue-800 break-keep whitespace-nowrap" href="#">Research + Teaching</a>
                </li>
                <p class="cursor-default">|</p>
                <li class="ml-2">
                    <a class="hover:text-blue-800" href="#">Contact</a>
                </li>
            </ul>
        </div>
    </div>
  
    <!-- Main Content -->
    <div class="grid grid-cols-1 md:grid-cols-2 gap-2 md:gap-6 my-auto">
      <div class="mb-2 bg-gray-300 mx-6 mt-8 md:mx-0 md:mt-0">
        <img src="./selfie.png" alt="background">
      </div>
        <p class="mt-10 mb-16 mx-10 px-2 md:mx-0 md:mt-0">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </p>
    </div>
  
    <!-- Social Media Icons -->
    <div class="grid grid-cols-1 md:grid-cols-2 gap-2 my-auto">
        <div>

        </div>
        <div class="social-media">
            <ul class="flex justify-center">
                <li class="mr-3">
                    <a class="hover:text-blue-800" href="./instagram.png">
                        <img class="w-6" src="./instagram.png" alt="background">
                    </a>
                </li>
                <li class="mx-3">
                    <a class="hover:text-blue-800" href="./twitter.png">
                        <img class="w-6" src="./twitter.png" alt="background">
                    </a>
                </li>
                <li class="mx-3">
                    <a class="hover:text-blue-800" href="./linkedin.png">
                        <img class="w-6" src="./linkedin.png" alt="background">
                    </a>
                </li>
                <li class="ml-3">
                    <a class="max-w-md hover:text-blue-800" href="./youtube.svg">
                        <img class="w-6" src="./youtube.svg" alt="background">
                    </a>
                </li>
            </ul>
        </div>
    </div>
  </div>
  
  <style>
    /* Add CSS styles for responsiveness */
  
    /* Mobile */
    @media (max-width: 640px) {
      .container {
        grid-template-columns: 1fr;
      }
      .nav-bar,
      .social-media {
        text-align: center;
      }
      .main-content {
        grid-template-columns: 1fr;
        margin: 0;
      }
      .my-4,
      .mt-10,
      .mb-16,
      .mr-20,
      .ml-20,
      .mx-4,
      .ml-8,
      .mr-6 {
        margin: 1rem;
      }
      .w-6 {
        width: 20px;
      }
    }
  
    /* Tablet */
    @media (min-width: 640px) and (max-width: 768px) {
      /* Adjust the styles as needed for tablet devices */
      /* Example: .text-4xl { font-size: ... } */
    }
  </style>
  