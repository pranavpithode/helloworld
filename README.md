
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>HireRadar - Find Jobs Around You</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-white text-gray-900">

  <!-- Navbar -->
  <header class="border-b">
    <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-blue-600">HireRadar</h1>
      <a href="#waitlist" class="px-4 py-2 bg-blue-600 text-white rounded-xl">Join Beta</a>
    </div>
  </header>

  <!-- Hero -->
  <section class="max-w-7xl mx-auto px-6 py-24 text-center">
    <h2 class="text-5xl font-bold leading-tight">
      Find Jobs Around You Instantly
    </h2>
    <p class="mt-6 text-lg text-gray-600 max-w-2xl mx-auto">
      HireRadar helps job seekers discover actively hiring companies on a live map.
      Explore nearby opportunities, apply faster, and get hired smarter.
    </p>

    <div class="mt-8 flex justify-center gap-4 flex-wrap">
      <a href="#waitlist" class="px-6 py-3 bg-blue-600 text-white rounded-xl text-lg">
        Join Waitlist
      </a>
      <a href="#recruiters" class="px-6 py-3 border rounded-xl text-lg">
        Recruiters Join Free
      </a>
    </div>
  </section>

  <!-- Features -->
  <section class="bg-gray-50 py-20">
    <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-3 gap-8">
      <div class="p-6 bg-white rounded-2xl shadow">
        <h3 class="text-xl font-semibold">📍 Jobs on Map</h3>
        <p class="mt-3 text-gray-600">
          View every active job around your location.
        </p>
      </div>

      <div class="p-6 bg-white rounded-2xl shadow">
        <h3 class="text-xl font-semibold">⚡ Quick Apply</h3>
        <p class="mt-3 text-gray-600">
          Apply to jobs in seconds with your profile.
        </p>
      </div>

      <div class="p-6 bg-white rounded-2xl shadow">
        <h3 class="text-xl font-semibold">🏢 Recruit Faster</h3>
        <p class="mt-3 text-gray-600">
          Companies reach nearby candidates instantly.
        </p>
      </div>
    </div>
  </section>

  <!-- Waitlist -->
  <section id="waitlist" class="py-24">
    <div class="max-w-xl mx-auto px-6 text-center">
      <h3 class="text-3xl font-bold">Join Early Access</h3>
      <p class="mt-4 text-gray-600">
        Be first to access HireRadar beta in Nashik, Pune & Mumbai.
      </p>

      <form class="mt-8 flex flex-col gap-4">
        <input type="text" placeholder="Your Name"
          class="border p-3 rounded-xl w-full"/>
        <input type="email" placeholder="Your Email"
          class="border p-3 rounded-xl w-full"/>
        <button class="bg-blue-600 text-white py-3 rounded-xl">
          Join Waitlist
        </button>
      </form>
    </div>
  </section>

  <!-- Recruiters -->
  <section id="recruiters" class="bg-blue-600 text-white py-20">
    <div class="max-w-4xl mx-auto px-6 text-center">
      <h3 class="text-4xl font-bold">Hiring? Join Free Beta</h3>
      <p class="mt-4 text-lg">
        Post jobs on map and reach nearby candidates faster.
      </p>

      <a href="#waitlist"
        class="inline-block mt-8 px-6 py-3 bg-white text-blue-600 rounded-xl font-semibold">
        Join as Recruiter
      </a>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-8 text-center text-gray-500">
    © 2026 HireRadar. All rights reserved.
  </footer>

</body>
</html>
