<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Enhanced UI Example</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.16/dist/tailwind.min.css" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css">
  <style>
    .shimmer {
      background: linear-gradient(to right, #f6f7f8 0%, #edeef1 50%, #f6f7f8 100%);
      background-size: 200% 200%;
      animation: shimmer 1.5s ease infinite;
    }

    @keyframes shimmer {
      0% {
        background-position: 0% 50%;
      }
      50% {
        background-position: 100% 50%;
      }
      100% {
        background-position: 0% 50%;
      }
    }
  </style>
</head>
<body class="bg-gray-100">
  <header class="bg-white shadow-md py-4">
    <div class="container mx-auto flex justify-between items-center">
      <a href="#" class="text-2xl font-bold text-blue-500">Enhanced UI</a>
      <nav>
        <ul class="flex space-x-4">
          <li><a href="#" class="hover:text-blue-500">Home</a></li>
          <li><a href="#" class="hover:text-blue-500">About</a></li>
          <li><a href="#" class="hover:text-blue-500">Services</a></li>
          <li><a href="#" class="hover:text-blue-500">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main class="container mx-auto py-8">
    <section class="mb-8">
      <h1 class="text-4xl font-bold mb-4">Welcome to Enhanced UI</h1>
      <p class="text-gray-600 mb-6">Discover the power of user-centric design and seamless experiences.</p>
      <div class="flex justify-center">
        <a href="#" class="bg-blue-500 hover:bg-blue-600 text-white font-bold py-3 px-6 rounded-lg">Get Started</a>
      </div>
    </section>

    <section class="mb-8">
      <h2 class="text-2xl font-bold mb-4">Our Services</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="bg-white shadow-md rounded-lg p-6">
          <div class="mb-4 shimmer h-32"></div>
          <h3 class="text-xl font-bold mb-2">UI Design</h3>
          <p class="text-gray-600">Crafting visually stunning and user-friendly interfaces.</p>
        </div>
        <div class="bg-white shadow-md rounded-lg p-6">
          <div class="mb-4 shimmer h-32"></div>
          <h3 class="text-xl font-bold mb-2">UX Research</h3>
          <p class="text-gray-600">Uncovering user insights to drive impactful design decisions.</p>
        </div>
        <div class="bg-white shadow-md rounded-lg p-6">
          <div class="mb-4 shimmer h-32"></div>
          <h3 class="text-xl font-bold mb-2">Web Development</h3>
          <p class="text-gray-600">Transforming designs into responsive, high-performing websites.</p>
        </div>
      </div>
    </section>

    <section class="mb-8">
      <h2 class="text-2xl font-bold mb-4">Why Choose Us?</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <div class="bg-white shadow-md rounded-lg p-6 flex items-center">
          <div class="text-blue-500 mr-4">
            <i class="fas fa-check-circle fa-2x"></i>
          </div>
          <div>
            <h3 class="text-xl font-bold mb-2">Attention to Detail</h3>
            <p class="text-gray-600">We meticulously craft every pixel to ensure a polished, seamless experience.</p>
          </div>
        </div>
        <div class="bg-white shadow-md rounded-lg p-6 flex items-center">
          <div class="text-blue-500 mr-4">
            <i class="fas fa-rocket fa-2x"></i>
          </div>
          <div>
            <h3 class="text-xl font-bold mb-2">Cutting-Edge Techniques</h3>
            <p class="text-gray-600">We stay ahead of the curve, leveraging the latest UI/UX design trends and technologies.</p>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer class="bg-gray-800 text-white py-6">
    <div class="container mx-auto flex justify-between items-center">
      <p>&copy; 2023 Enhanced UI. All rights reserved.</p>
      <div class="flex space-x-4">
        <a href="#" class="hover:text-blue-500"><i class="fab fa-facebook fa-lg"></i></a>
        <a href="#" class="hover:text-blue-500"><i class="fab fa-twitter fa-lg"></i></a>
        <a href="#" class="hover:text-blue-500"><i class="fab fa-linkedin fa-lg"></i></a>
      </div>
    </div>
  </footer>
</body>
</html>
