<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Style Bande | Bandes à joint, Enduits & Peinture - Saint-Herblain</title>
  <meta name="description" content="Entreprise artisanale à Saint-Herblain spécialisée dans les bandes à joint, enduits et peinture intérieure. Finitions soignées et devis gratuits.">

  <!-- Tailwind CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <style>
    /* Simple animation pour les images et titres */
    .fade-in { opacity: 0; transform: translateY(20px); animation: fadeIn 0.8s forwards; }
    .fade-in.delay-1 { animation-delay: 0.2s; }
    .fade-in.delay-2 { animation-delay: 0.4s; }
    .fade-in.delay-3 { animation-delay: 0.6s; }

    @keyframes fadeIn {
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body class="font-sans text-gray-900 bg-gradient-to-b from-gray-50 to-gray-200">

  <!-- Header -->
  <header class="bg-white/90 backdrop-blur shadow-sm sticky top-0 z-50">
    <div class="max-w-6xl mx-auto px-6 lg:px-8 flex items-center justify-between h-16">
      <div class="flex items-center gap-3">
        <div class="w-12 h-12 rounded-lg bg-gradient-to-br from-yellow-400 to-orange-500 flex items-center justify-center text-white font-bold">SB</div>
        <div>
          <a href="#home" class="text-lg font-semibold">Style Bande</a>
          <div class="text-xs text-gray-500">Bandes • Enduits • Peinture</div>
        </div>
      </div>

      <nav class="hidden md:flex gap-6 text-sm">
        <a href="#services" class="hover:text-orange-600">Services</a>
        <a href="#realisations" class="hover:text-orange-600">Réalisations</a>
        <a href="#apropos" class="hover:text-orange-600">À propos</a>
        <a href="#contact" class="px-4 py-2 bg-orange-500 text-white rounded-md shadow-sm hover:bg-orange-600">Devis</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="home" class="py-20 lg:py-28 bg-gradient-to-br from-orange-50 to-white">
    <div class="max-w-6xl mx-auto px-6 grid grid-cols-1 lg:grid-cols-2 gap-10 items-center">
      <div class="fade-in">
        <h1 class="text-4xl font-extrabold leading-tight">Finitions pro pour plaques de plâtre — bandes, enduits, peinture</h1>
        <p class="mt-4 text-gray-600">Pose soignée de bandes à joint, égalisation des murs, finitions peinture et retouches. Travail propre, respect des délais et devis clair.</p>
        <div class="mt-6 flex gap-4">
          <a href="#contact" class="inline-block px-6 py-3 bg-orange-500 text-white rounded-md shadow hover:bg-orange-600 transition">Demander un devis</a>
          <a href="#realisations" class="inline-block px-6 py-3 border border-gray-300 rounded-md hover:bg-gray-100 transition">Voir réalisations</a>
        </div>
        <p class="mt-6 text-sm text-gray-500"><strong>Basé à :</strong> Saint-Herblain — Intervention Loire-Atlantique</p>
      </div>
      <div class="fade-in delay-1">
        <img src="https://images.unsplash.com/photo-1524758631624-e2822e304c36?auto=format&fit=crop&w=1200&q=60" alt="Travail de plâtrerie" class="rounded-xl shadow-lg w-full h-80 object-cover" />
      </div>
    </div>
  </section>

  <!-- Services -->
  <section id="services" class="max-w-6xl mx-auto px-6 lg:px-8 py-16">
    <h2 class="text-3xl font-bold fade-in">Nos services</h2>
    <p class="mt-2 text-gray-600 fade-in delay-1">Pour particuliers et professionnels — qualité, propreté, et finitions parfaites.</p>
    <div class="mt-8 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
      <div class="bg-white rounded-lg p-6 shadow hover:shadow-md transition border border-gray-100 fade-in delay-1">
        <div class="text-3xl">🧱</div>
        <h3 class="mt-3 font-semibold text-lg">Pose de bandes à joint</h3>
        <p class="mt-1 text-sm text-gray-600">Bandes papier et fibre, angles, reprise des défauts.</p>
      </div>
      <div class="bg-white rounded-lg p-6 shadow hover:shadow-md transition border border-gray-100 fade-in delay-2">
        <div class="text-3xl">🪚</div>
        <h3 class="mt-3 font-semibold text-lg">Enduits & Lissage</h3>
        <p class="mt-1 text-sm text-gray-600">Couches d'enduit, ponçage et préparation peinture.</p>
      </div>
      <div class="bg-white rounded-lg p-6 shadow hover:shadow-md transition border border-gray-100 fade-in delay-3">
        <div class="text-3xl">🎨</div>
        <h3 class="mt-3 font-semibold text-lg">Peinture intérieure</h3>
        <p class="mt-1 text-sm text-gray-600">Finition mate, satinée, réparations et retouches.</p>
      </div>
    </div>
  </section>

  <!-- Réalisations -->
  <section id="realisations" class="bg-white py-16">
    <div class="max-w-6xl mx-auto px-6 lg:px-8">
      <h2 class="text-3xl font-bold fade-in">Réalisations récentes</h2>
      <p class="mt-2 text-gray-600 fade-in delay-1">Avant / Après — chantiers de rénovation, peinture et finition placo.</p>
      <div class="mt-8 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
        <img src="https://static.wixstatic.com/media/1b0e1b_0c80e19b6a914ffb8fa9a1c7eaa3213b~mv2.jpg" class="w-full h-52 object-cover rounded-md shadow-md fade-in delay-1"/>
        <img src="https://static.wixstatic.com/media/1b0e1b_ebdb9a16b98e42f4a3f75de4bfc68f36~mv2.jpg" class="w-full h-52 object-cover rounded-md shadow-md fade-in delay-2"/>
        <img src="https://static.wixstatic.com/media/1b0e1b_5a48b3528f7a496d8a003f0ec8ab0df1~mv2.jpg" class="w-full h-52 object-cover rounded-md shadow-md fade-in delay-3"/>
        <img src="https://static.wixstatic.com/media/1b0e1b_1c827e304c8d4033a3d969712c0ef5a5~mv2.jpg" class="w-full h-52 object-cover rounded-md shadow-md fade-in delay-1"/>
        <img src="https://static.wixstatic.com/media/1b0e1b_22cc9f9b73ad48efba918e35a38a3b9c~mv2.jpg" class="w-full h-52 object-cover rounded-md shadow-md fade-in delay-2"/>
        <img src="https://static.wixstatic.com/media/1b0e1b_84ad8bb8e7cd45d7b1c9f4ab8a3f1a25~mv2.jpg" class="w-full h-52 object-cover rounded-md shadow-md fade-in delay-3"/>
      </div>
    </div>
  </section>

  <!-- À propos -->
  <section id="apropos" class="max-w-6xl mx-auto px-6 lg:px-8 py-16 grid grid-cols-1 lg:grid-cols-3 gap-6 items-center">
    <div class="lg:col-span-2 fade-in">
      <h2 class="text-3xl font-bold">À propos de Style Bande</h2>
      <p class="mt-3 text-gray-600">Entreprise artisanale fondée par un jointeur expérimenté — savoir-faire acquis depuis plus de 15 ans. Chantier propre, finitions soignées et délais respectés.</p>
      <ul class="mt-4 grid grid-cols-1 sm:grid-cols-2 gap-2 text-sm text-gray-700">
        <li>✅ Devis gratuit</li>
        <li>✅ Assurance décennale</li>
        <li>✅ Intervention Loire-Atlantique</li>
        <li>✅ Respect des délais</li>
      </ul>
    </div>
    <div class="rounded-lg bg-gray-100 p-6 shadow-sm fade-in delay-1">
      <h3 class="font-semibold">Contact rapide</h3>
      <p class="text-sm text-gray-600 mt-2">Téléphone : <a href="tel:+33661950859" class="text-orange-600">06 61 95 08 59</a></p>
      <p class="text-sm text-gray-600 mt-1">Adresse : Saint-Herblain (44)</p>
      <a href="#contact" class="mt-4 inline-block px-4 py-2 bg-orange-500 text-white rounded-md">Envoyer un message</a>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="bg-white py-16">
    <div class="max-w-4xl mx-auto px-6 lg:px-8">
      <h2 class="text-3xl font-bold fade-in">Contact & Devis</h2>
      <p class="mt-2 text-gray-600 fade-in delay-1">Remplis ce formulaire, je te réponds rapidement — ou appelle directement.</p>
      <form class="mt-8 grid grid-cols-1 gap-4">
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
          <input class="p-3 rounded-md border" name="nom" placeholder="Nom" required>
          <input class="p-3 rounded-md border" name="telephone" placeholder="Téléphone" required>
        </div>
        <input class="p-3 rounded-md border" name="email" placeholder="Email" type="email" required>
        <textarea class="p-3 rounded-md border h-32" name="message" placeholder="Message / détails du chantier..." required></textarea>
        <div class="flex items-center gap-4">
          <button type="submit" class="px-6 py-3 bg-orange-500 text-white rounded-md shadow hover:bg-orange-600">Envoyer</button>
          <a href="tel:+33661950859" class="text-sm text-gray-600">Ou appeler : 06 61 95 08 59</a>
        </div>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-gray-300 py-8 mt-12">
    <div class="max-w-6xl mx-auto px-6 lg:px-8 flex flex-col md:flex-row justify-between items-center gap-4">
      <div class="w-12 h-12 rounded-lg bg-gradient-to-br from-yellow-400 to-orange-500 flex items-center justify-center text-white font-bold">SB</div>
      <div class="text-sm text-gray-400">© 2025 Style Bande — Saint-Herblain. Tous droits réservés.</div>
    </div>
  </footer>

</body>
</html>
