<!doctype html>
<html lang="en"> 
 <head> 
  <meta charset="utf-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>Maktab Ul Razviya Library</title> 
  <script src="https://cdn.tailwindcss.com"></script> 
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"> 
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&amp;display=swap" rel="stylesheet"> 
  <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f8f9fa;
        }
        .nav-black {
            background: black;
        }
        .book-slider {
            display: flex;
            overflow-x: auto;
            scroll-behavior: smooth;
            gap: 20px;
            padding: 10px;
        }
        .book-slider::-webkit-scrollbar {
            display: none;
        }
        .book-card {
            min-width: 250px;
            background: white;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s;
            text-align: center;
        }
        .book-card:hover {
            transform: scale(1.05);
        }
        .gradient-text {
            background: linear-gradient(to right, #6a11cb, #2575fc);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: bold;
            text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.2);
        }
        .search-section {
            position: relative;
            text-align: center;
            color: white;
            padding: 60px 0;
            font-weight: bold;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }
        .search-section h1 {
            color: #fff;
            font-size: 2.5rem;
            font-weight: 700;
            text-shadow: 3px 3px 10px rgba(0, 0, 0, 0.8);
        }
        .search-section p {
            color: #f1f1f1;
            font-size: 1.2rem;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.6);
        }
        .search-section::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://i.ibb.co/FLzFtgFn/Screenshot-20250301-150539.png') no-repeat center center/cover;
            opacity: 0.6;
            z-index: -1;
        }
  </style> 
 </head> 
 <body class="bg-gray-100 text-gray-800"> 
  <header class="nav-black text-white shadow-md py-4"> 
   <div class="container mx-auto px-4 flex justify-between items-center"> 
    <div class="text-2xl font-bold">
      Maktab Ul Razviya Library 
    </div> 
    <nav class="space-x-4"> 
      <a class="hover:underline" href="#">Home</a> 
      <a class="hover:underline" href="#">Books</a> 
      <a class="hover:underline" href="#">About</a> 
      <a class="hover:underline" href="#">Contact</a> 
    </nav> 
   </div> 
  </header> 

  <!-- Search & Welcome Section -->
  <section class="search-section"> 
   <div class="container mx-auto"> 
    <h1>Welcome to Maktab Ul Razviya Library</h1> 
    <p class="mt-4">Your source for authentic Islamic books and knowledge.</p> 
    <div class="mt-6 flex justify-center"> 
     <input type="text" placeholder="Search Books..." class="px-4 py-2 border rounded-lg w-1/2 text-gray-900"> 
     <button class="ml-2 bg-white text-black px-4 py-2 rounded-lg">Search</button> 
    </div> 
   </div> 
  </section> 

  <!-- Latest Books Section -->
  <section class="py-12 bg-white text-gray-900 shadow-md"> 
   <div class="container mx-auto px-4"> 
    <h2 class="text-3xl gradient-text text-center mb-6">Latest Books</h2> 
    <div class="book-slider"> 
     <div class="book-card"> 
      <h3 class="text-lg font-bold mt-2">Tafseer-e-Raza</h3> 
      <p>Author: Imam Ahmad Raza</p> 
      <p>Views: 1.5K | Downloads: 700</p> 
      <p>Rating: ⭐⭐⭐⭐⭐</p> 
     </div> 
     <div class="book-card"> 
      <h3 class="text-lg font-bold mt-2">Islamic Jurisprudence</h3> 
      <p>Author: Dr. Muhammad Ali</p> 
      <p>Views: 2.1K | Downloads: 900</p> 
      <p>Rating: ⭐⭐⭐⭐⭐</p> 
     </div> 
    </div> 
   </div> 
  </section> 

  <!-- Popular Books Section -->
  <section class="py-12 bg-gray-100 text-gray-900"> 
   <div class="container mx-auto px-4"> 
    <h2 class="text-3xl gradient-text text-center mb-6">Popular Books</h2> 
    <div class="book-slider"> 
     <div class="book-card"> 
      <h3 class="text-lg font-bold mt-2">Aqaid-e-Ahle Sunnat</h3> 
      <p>Author: Imam Ahmad Raza</p> 
      <p>Views: 5.3K | Downloads: 2.5K</p> 
      <p>Rating: ⭐⭐⭐⭐⭐</p> 
     </div> 
     <div class="book-card"> 
      <h3 class="text-lg font-bold mt-2">Faza'il-e-Durood Shareef</h3> 
      <p>Author: Allama Arshadul Qadri</p> 
      <p>Views: 4.8K | Downloads: 2.1K</p> 
      <p>Rating: ⭐⭐⭐⭐⭐</p> 
     </div> 
    </div> 
   </div> 
  </section> 

  <!-- About Section -->
  <section class="py-12 bg-white text-gray-900 text-center"> 
   <h2 class="text-3xl font-bold mb-6">About Us</h2> 
   <p class="text-lg">Alhamdulillah Majlis e Raza Committee ki janib se Awam e Ahle Sunnat ke liye ek behtareen website pesh e khidmat hai.</p> 
  </section> 

  <footer class="bg-gray-800 py-8 text-white text-center"> 
   <p>© 2025 Maktab Ul Razviya Library. All rights reserved.</p> 
  </footer> 
 </body>
</html><!doctype html>
<html lang="en"> 
 <head> 
  <meta charset="utf-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>Maktab Ul Razviya Library</title> 
  <script src="https://cdn.tailwindcss.com"></script> 
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"> 
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&amp;display=swap" rel="stylesheet"> 
  <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f8f9fa;
        }
        .nav-black {
            background: black;
        }
        .book-slider {
            display: flex;
            overflow-x: auto;
            scroll-behavior: smooth;
            gap: 20px;
            padding: 10px;
        }
        .book-slider::-webkit-scrollbar {
            display: none;
        }
        .book-card {
            min-width: 250px;
            background: white;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s;
            text-align: center;
        }
        .book-card:hover {
            transform: scale(1.05);
        }
        .gradient-text {
            background: linear-gradient(to right, #6a11cb, #2575fc);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: bold;
            text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.2);
        }
        .search-section {
            position: relative;
            text-align: center;
            color: white;
            padding: 60px 0;
            font-weight: bold;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }
        .search-section h1 {
            color: #fff;
            font-size: 2.5rem;
            font-weight: 700;
            text-shadow: 3px 3px 10px rgba(0, 0, 0, 0.8);
        }
        .search-section p {
            color: #f1f1f1;
            font-size: 1.2rem;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.6);
        }
        .search-section::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://i.ibb.co/FLzFtgFn/Screenshot-20250301-150539.png') no-repeat center center/cover;
            opacity: 0.6;
            z-index: -1;
        }
  </style> 
 </head> 
 <body class="bg-gray-100 text-gray-800"> 
  <header class="nav-black text-white shadow-md py-4"> 
   <div class="container mx-auto px-4 flex justify-between items-center"> 
    <div class="text-2xl font-bold">
      Maktab Ul Razviya Library 
    </div> 
    <nav class="space-x-4"> 
      <a class="hover:underline" href="#">Home</a> 
      <a class="hover:underline" href="#">Books</a> 
      <a class="hover:underline" href="#">About</a> 
      <a class="hover:underline" href="#">Contact</a> 
    </nav> 
   </div> 
  </header> 

  <!-- Search & Welcome Section -->
  <section class="search-section"> 
   <div class="container mx-auto"> 
    <h1>Welcome to Maktab Ul Razviya Library</h1> 
    <p class="mt-4">Your source for authentic Islamic books and knowledge.</p> 
    <div class="mt-6 flex justify-center"> 
     <input type="text" placeholder="Search Books..." class="px-4 py-2 border rounded-lg w-1/2 text-gray-900"> 
     <button class="ml-2 bg-white text-black px-4 py-2 rounded-lg">Search</button> 
    </div> 
   </div> 
  </section> 

  <!-- Latest Books Section -->
  <section class="py-12 bg-white text-gray-900 shadow-md"> 
   <div class="container mx-auto px-4"> 
    <h2 class="text-3xl gradient-text text-center mb-6">Latest Books</h2> 
    <div class="book-slider"> 
     <div class="book-card"> 
      <h3 class="text-lg font-bold mt-2">Tafseer-e-Raza</h3> 
      <p>Author: Imam Ahmad Raza</p> 
      <p>Views: 1.5K | Downloads: 700</p> 
      <p>Rating: ⭐⭐⭐⭐⭐</p> 
     </div> 
     <div class="book-card"> 
      <h3 class="text-lg font-bold mt-2">Islamic Jurisprudence</h3> 
      <p>Author: Dr. Muhammad Ali</p> 
      <p>Views: 2.1K | Downloads: 900</p> 
      <p>Rating: ⭐⭐⭐⭐⭐</p> 
     </div> 
    </div> 
   </div> 
  </section> 

  <!-- Popular Books Section -->
  <section class="py-12 bg-gray-100 text-gray-900"> 
   <div class="container mx-auto px-4"> 
    <h2 class="text-3xl gradient-text text-center mb-6">Popular Books</h2> 
    <div class="book-slider"> 
     <div class="book-card"> 
      <h3 class="text-lg font-bold mt-2">Aqaid-e-Ahle Sunnat</h3> 
      <p>Author: Imam Ahmad Raza</p> 
      <p>Views: 5.3K | Downloads: 2.5K</p> 
      <p>Rating: ⭐⭐⭐⭐⭐</p> 
     </div> 
     <div class="book-card"> 
      <h3 class="text-lg font-bold mt-2">Faza'il-e-Durood Shareef</h3> 
      <p>Author: Allama Arshadul Qadri</p> 
      <p>Views: 4.8K | Downloads: 2.1K</p> 
      <p>Rating: ⭐⭐⭐⭐⭐</p> 
     </div> 
    </div> 
   </div> 
  </section> 

  <!-- About Section -->
  <section class="py-12 bg-white text-gray-900 text-center"> 
   <h2 class="text-3xl font-bold mb-6">About Us</h2> 
   <p class="text-lg">Alhamdulillah Majlis e Raza Committee ki janib se Awam e Ahle Sunnat ke liye ek behtareen website pesh e khidmat hai.</p> 
  </section> 

  <footer class="bg-gray-800 py-8 text-white text-center"> 
   <p>© 2025 Maktab Ul Razviya Library. All rights reserved.</p> 
  </footer> 
 </body>
</html><!doctype html>
<html lang="en"> 
 <head> 
  <meta charset="utf-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>Maktab Ul Razviya Library</title> 
  <script src="https://cdn.tailwindcss.com"></script> 
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"> 
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&amp;display=swap" rel="stylesheet"> 
  <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f8f9fa;
        }
        .nav-black {
            background: black;
        }
        .book-slider {
            display: flex;
            overflow-x: auto;
            scroll-behavior: smooth;
            gap: 20px;
            padding: 10px;
        }
        .book-slider::-webkit-scrollbar {
            display: none;
        }
        .book-card {
            min-width: 250px;
            background: white;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s;
            text-align: center;
        }
        .book-card:hover {
            transform: scale(1.05);
        }
        .gradient-text {
            background: linear-gradient(to right, #6a11cb, #2575fc);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: bold;
            text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.2);
        }
        .search-section {
            position: relative;
            text-align: center;
            color: white;
            padding: 60px 0;
            font-weight: bold;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }
        .search-section h1 {
            color: #fff;
            font-size: 2.5rem;
            font-weight: 700;
            text-shadow: 3px 3px 10px rgba(0, 0, 0, 0.8);
        }
        .search-section p {
            color: #f1f1f1;
            font-size: 1.2rem;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.6);
        }
        .search-section::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://i.ibb.co/FLzFtgFn/Screenshot-20250301-150539.png') no-repeat center center/cover;
            opacity: 0.6;
            z-index: -1;
        }
  </style> 
 </head> 
 <body class="bg-gray-100 text-gray-800"> 
  <header class="nav-black text-white shadow-md py-4"> 
   <div class="container mx-auto px-4 flex justify-between items-center"> 
    <div class="text-2xl font-bold">
      Maktab Ul Razviya Library 
    </div> 
    <nav class="space-x-4"> 
      <a class="hover:underline" href="#">Home</a> 
      <a class="hover:underline" href="#">Books</a> 
      <a class="hover:underline" href="#">About</a> 
      <a class="hover:underline" href="#">Contact</a> 
    </nav> 
   </div> 
  </header> 

  <!-- Search & Welcome Section -->
  <section class="search-section"> 
   <div class="container mx-auto"> 
    <h1>Welcome to Maktab Ul Razviya Library</h1> 
    <p class="mt-4">Your source for authentic Islamic books and knowledge.</p> 
    <div class="mt-6 flex justify-center"> 
     <input type="text" placeholder="Search Books..." class="px-4 py-2 border rounded-lg w-1/2 text-gray-900"> 
     <button class="ml-2 bg-white text-black px-4 py-2 rounded-lg">Search</button> 
    </div> 
   </div> 
  </section> 

  <!-- Latest Books Section -->
  <section class="py-12 bg-white text-gray-900 shadow-md"> 
   <div class="container mx-auto px-4"> 
    <h2 class="text-3xl gradient-text text-center mb-6">Latest Books</h2> 
    <div class="book-slider"> 
     <div class="book-card"> 
      <h3 class="text-lg font-bold mt-2">Tafseer-e-Raza</h3> 
      <p>Author: Imam Ahmad Raza</p> 
      <p>Views: 1.5K | Downloads: 700</p> 
      <p>Rating: ⭐⭐⭐⭐⭐</p> 
     </div> 
     <div class="book-card"> 
      <h3 class="text-lg font-bold mt-2">Islamic Jurisprudence</h3> 
      <p>Author: Dr. Muhammad Ali</p> 
      <p>Views: 2.1K | Downloads: 900</p> 
      <p>Rating: ⭐⭐⭐⭐⭐</p> 
     </div> 
    </div> 
   </div> 
  </section> 

  <!-- Popular Books Section -->
  <section class="py-12 bg-gray-100 text-gray-900"> 
   <div class="container mx-auto px-4"> 
    <h2 class="text-3xl gradient-text text-center mb-6">Popular Books</h2> 
    <div class="book-slider"> 
     <div class="book-card"> 
      <h3 class="text-lg font-bold mt-2">Aqaid-e-Ahle Sunnat</h3> 
      <p>Author: Imam Ahmad Raza</p> 
      <p>Views: 5.3K | Downloads: 2.5K</p> 
      <p>Rating: ⭐⭐⭐⭐⭐</p> 
     </div> 
     <div class="book-card"> 
      <h3 class="text-lg font-bold mt-2">Faza'il-e-Durood Shareef</h3> 
      <p>Author: Allama Arshadul Qadri</p> 
      <p>Views: 4.8K | Downloads: 2.1K</p> 
      <p>Rating: ⭐⭐⭐⭐⭐</p> 
     </div> 
    </div> 
   </div> 
  </section> 

  <!-- About Section -->
  <section class="py-12 bg-white text-gray-900 text-center"> 
   <h2 class="text-3xl font-bold mb-6">About Us</h2> 
   <p class="text-lg">Alhamdulillah Majlis e Raza Committee ki janib se Awam e Ahle Sunnat ke liye ek behtareen website pesh e khidmat hai.</p> 
  </section> 

  <footer class="bg-gray-800 py-8 text-white text-center"> 
   <p>© 2025 Maktab Ul Razviya Library. All rights reserved.</p> 
  </footer> 
 </body>
</html><!doctype html>
<html lang="en"> 
 <head> 
  <meta charset="utf-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>Maktab Ul Razviya Library</title> 
  <script src="https://cdn.tailwindcss.com"></script> 
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"> 
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&amp;display=swap" rel="stylesheet"> 
  <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f8f9fa;
        }
        .nav-black {
            background: black;
        }
        .book-slider {
            display: flex;
            overflow-x: auto;
            scroll-behavior: smooth;
            gap: 20px;
            padding: 10px;
        }
        .book-slider::-webkit-scrollbar {
            display: none;
        }
        .book-card {
            min-width: 250px;
            background: white;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s;
            text-align: center;
        }
        .book-card:hover {
            transform: scale(1.05);
        }
        .gradient-text {
            background: linear-gradient(to right, #6a11cb, #2575fc);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: bold;
            text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.2);
        }
        .search-section {
            position: relative;
            text-align: center;
            color: white;
            padding: 60px 0;
            font-weight: bold;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }
        .search-section h1 {
            color: #fff;
            font-size: 2.5rem;
            font-weight: 700;
            text-shadow: 3px 3px 10px rgba(0, 0, 0, 0.8);
        }
        .search-section p {
            color: #f1f1f1;
            font-size: 1.2rem;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.6);
        }
        .search-section::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://i.ibb.co/FLzFtgFn/Screenshot-20250301-150539.png') no-repeat center center/cover;
            opacity: 0.6;
            z-index: -1;
        }
  </style> 
 </head> 
 <body class="bg-gray-100 text-gray-800"> 
  <header class="nav-black text-white shadow-md py-4"> 
   <div class="container mx-auto px-4 flex justify-between items-center"> 
    <div class="text-2xl font-bold">
      Maktab Ul Razviya Library 
    </div> 
    <nav class="space-x-4"> 
      <a class="hover:underline" href="#">Home</a> 
      <a class="hover:underline" href="#">Books</a> 
      <a class="hover:underline" href="#">About</a> 
      <a class="hover:underline" href="#">Contact</a> 
    </nav> 
   </div> 
  </header> 

  <!-- Search & Welcome Section -->
  <section class="search-section"> 
   <div class="container mx-auto"> 
    <h1>Welcome to Maktab Ul Razviya Library</h1> 
    <p class="mt-4">Your source for authentic Islamic books and knowledge.</p> 
    <div class="mt-6 flex justify-center"> 
     <input type="text" placeholder="Search Books..." class="px-4 py-2 border rounded-lg w-1/2 text-gray-900"> 
     <button class="ml-2 bg-white text-black px-4 py-2 rounded-lg">Search</button> 
    </div> 
   </div> 
  </section> 

  <!-- Latest Books Section -->
  <section class="py-12 bg-white text-gray-900 shadow-md"> 
   <div class="container mx-auto px-4"> 
    <h2 class="text-3xl gradient-text text-center mb-6">Latest Books</h2> 
    <div class="book-slider"> 
     <div class="book-card"> 
      <h3 class="text-lg font-bold mt-2">Tafseer-e-Raza</h3> 
      <p>Author: Imam Ahmad Raza</p> 
      <p>Views: 1.5K | Downloads: 700</p> 
      <p>Rating: ⭐⭐⭐⭐⭐</p> 
     </div> 
     <div class="book-card"> 
      <h3 class="text-lg font-bold mt-2">Islamic Jurisprudence</h3> 
      <p>Author: Dr. Muhammad Ali</p> 
      <p>Views: 2.1K | Downloads: 900</p> 
      <p>Rating: ⭐⭐⭐⭐⭐</p> 
     </div> 
    </div> 
   </div> 
  </section> 

  <!-- Popular Books Section -->
  <section class="py-12 bg-gray-100 text-gray-900"> 
   <div class="container mx-auto px-4"> 
    <h2 class="text-3xl gradient-text text-center mb-6">Popular Books</h2> 
    <div class="book-slider"> 
     <div class="book-card"> 
      <h3 class="text-lg font-bold mt-2">Aqaid-e-Ahle Sunnat</h3> 
      <p>Author: Imam Ahmad Raza</p> 
      <p>Views: 5.3K | Downloads: 2.5K</p> 
      <p>Rating: ⭐⭐⭐⭐⭐</p> 
     </div> 
     <div class="book-card"> 
      <h3 class="text-lg font-bold mt-2">Faza'il-e-Durood Shareef</h3> 
      <p>Author: Allama Arshadul Qadri</p> 
      <p>Views: 4.8K | Downloads: 2.1K</p> 
      <p>Rating: ⭐⭐⭐⭐⭐</p> 
     </div> 
    </div> 
   </div> 
  </section> 

  <!-- About Section -->
  <section class="py-12 bg-white text-gray-900 text-center"> 
   <h2 class="text-3xl font-bold mb-6">About Us</h2> 
   <p class="text-lg">Alhamdulillah Majlis e Raza Committee ki janib se Awam e Ahle Sunnat ke liye ek behtareen website pesh e khidmat hai.</p> 
  </section> 

  <footer class="bg-gray-800 py-8 text-white text-center"> 
   <p>© 2025 Maktab Ul Razviya Library. All rights reserved.</p> 
  </footer> 
 </body>
</html><!doctype html>
<html lang="en"> 
 <head> 
  <meta charset="utf-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>Maktab Ul Razviya Library</title> 
  <script src="https://cdn.tailwindcss.com"></script> 
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"> 
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&amp;display=swap" rel="stylesheet"> 
  <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f8f9fa;
        }
        .nav-black {
            background: black;
        }
        .book-slider {
            display: flex;
            overflow-x: auto;
            scroll-behavior: smooth;
            gap: 20px;
            padding: 10px;
        }
        .book-slider::-webkit-scrollbar {
            display: none;
        }
        .book-card {
            min-width: 250px;
            background: white;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s;
            text-align: center;
        }
        .book-card:hover {
            transform: scale(1.05);
        }
        .gradient-text {
            background: linear-gradient(to right, #6a11cb, #2575fc);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: bold;
            text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.2);
        }
        .search-section {
            position: relative;
            text-align: center;
            color: white;
            padding: 60px 0;
            font-weight: bold;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }
        .search-section h1 {
            color: #fff;
            font-size: 2.5rem;
            font-weight: 700;
            text-shadow: 3px 3px 10px rgba(0, 0, 0, 0.8);
        }
        .search-section p {
            color: #f1f1f1;
            font-size: 1.2rem;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.6);
        }
        .search-section::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://i.ibb.co/FLzFtgFn/Screenshot-20250301-150539.png') no-repeat center center/cover;
            opacity: 0.6;
            z-index: -1;
        }
  </style> 
 </head> 
 <body class="bg-gray-100 text-gray-800"> 
  <header class="nav-black text-white shadow-md py-4"> 
   <div class="container mx-auto px-4 flex justify-between items-center"> 
    <div class="text-2xl font-bold">
      Maktab Ul Razviya Library 
    </div> 
    <nav class="space-x-4"> 
      <a class="hover:underline" href="#">Home</a> 
      <a class="hover:underline" href="#">Books</a> 
      <a class="hover:underline" href="#">About</a> 
      <a class="hover:underline" href="#">Contact</a> 
    </nav> 
   </div> 
  </header> 

  <!-- Search & Welcome Section -->
  <section class="search-section"> 
   <div class="container mx-auto"> 
    <h1>Welcome to Maktab Ul Razviya Library</h1> 
    <p class="mt-4">Your source for authentic Islamic books and knowledge.</p> 
    <div class="mt-6 flex justify-center"> 
     <input type="text" placeholder="Search Books..." class="px-4 py-2 border rounded-lg w-1/2 text-gray-900"> 
     <button class="ml-2 bg-white text-black px-4 py-2 rounded-lg">Search</button> 
    </div> 
   </div> 
  </section> 

  <!-- Latest Books Section -->
  <section class="py-12 bg-white text-gray-900 shadow-md"> 
   <div class="container mx-auto px-4"> 
    <h2 class="text-3xl gradient-text text-center mb-6">Latest Books</h2> 
    <div class="book-slider"> 
     <div class="book-card"> 
      <h3 class="text-lg font-bold mt-2">Tafseer-e-Raza</h3> 
      <p>Author: Imam Ahmad Raza</p> 
      <p>Views: 1.5K | Downloads: 700</p> 
      <p>Rating: ⭐⭐⭐⭐⭐</p> 
     </div> 
     <div class="book-card"> 
      <h3 class="text-lg font-bold mt-2">Islamic Jurisprudence</h3> 
      <p>Author: Dr. Muhammad Ali</p> 
      <p>Views: 2.1K | Downloads: 900</p> 
      <p>Rating: ⭐⭐⭐⭐⭐</p> 
     </div> 
    </div> 
   </div> 
  </section> 

  <!-- Popular Books Section -->
  <section class="py-12 bg-gray-100 text-gray-900"> 
   <div class="container mx-auto px-4"> 
    <h2 class="text-3xl gradient-text text-center mb-6">Popular Books</h2> 
    <div class="book-slider"> 
     <div class="book-card"> 
      <h3 class="text-lg font-bold mt-2">Aqaid-e-Ahle Sunnat</h3> 
      <p>Author: Imam Ahmad Raza</p> 
      <p>Views: 5.3K | Downloads: 2.5K</p> 
      <p>Rating: ⭐⭐⭐⭐⭐</p> 
     </div> 
     <div class="book-card"> 
      <h3 class="text-lg font-bold mt-2">Faza'il-e-Durood Shareef</h3> 
      <p>Author: Allama Arshadul Qadri</p> 
      <p>Views: 4.8K | Downloads: 2.1K</p> 
      <p>Rating: ⭐⭐⭐⭐⭐</p> 
     </div> 
    </div> 
   </div> 
  </section> 

  <!-- About Section -->
  <section class="py-12 bg-white text-gray-900 text-center"> 
   <h2 class="text-3xl font-bold mb-6">About Us</h2> 
   <p class="text-lg">Alhamdulillah Majlis e Raza Committee ki janib se Awam e Ahle Sunnat ke liye ek behtareen website pesh e khidmat hai.</p> 
  </section> 

  <footer class="bg-gray-800 py-8 text-white text-center"> 
   <p>© 2025 Maktab Ul Razviya Library. All rights reserved.</p> 
  </footer> 
 </body>
</html>
