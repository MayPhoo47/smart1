
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Profile of Three Candidates</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&family=Inter:wght@300;400;500;600&display=swap');
    
    body {
      font-family: 'Inter', sans-serif;
      background: linear-gradient(180deg, #7c3aed 0%, #ec4899 15%, #f59e0b 30%, #043424 45%, #245099 60%, #4d318d 75%, #922828 90%, #9e4506 100%);
      min-height: 100vh;
    }

   @media (max-width: 639px) {
  .px-4 {
    padding-left: 20px !important;
    padding-right: 20px !important;
  }
}


    /* .premium-bg {
      background: radial-gradient(circle at 20% 50%, rgba(89, 13, 51, 0.4), transparent 50%),
                  radial-gradient(circle at 80% 20%, rgba(245, 158, 11, 0.4), transparent 50%),
                  radial-gradient(circle at 40% 80%, rgba(16, 185, 129, 0.4), transparent 50%),
                  radial-gradient(circle at 60% 40%, rgba(52, 28, 108, 0.4), transparent 50%),
                  radial-gradient(circle at 10% 90%, rgba(239, 68, 68, 0.3), transparent 50%),
                  radial-gradient(circle at 90% 10%, rgba(194, 86, 9, 0.3), transparent 50%);
    } */

    .candidate-card {
      background: rgba(255, 255, 255, 0.25);
      backdrop-filter: blur(25px);
      border: 2px solid rgba(255, 255, 255, 0.4);
      transition: all 0.6s ease;
      position: relative;
      overflow: hidden;
      max-width: 350px;
      box-shadow: 0 8px 30px rgba(0, 0, 0, 0.2);
    }

    .candidate-card:hover {
      transform: translateY(-10px) scale(1.02);
      background: rgba(255, 255, 255, 0.35);
    }

    .premium-title {
      font-family: 'Playfair Display', serif;
      color: #000;
    }

    .policy-dot {
      background: linear-gradient(135deg, #ec4899, #f59e0b, #10b981, #8b5cf6);
      box-shadow: 0 0 10px rgba(236, 72, 153, 0.4);
    }
  </style>
</head>
<body class="premium-bg relative">
  <div class="container mx-auto px-4 sm:px-6 md:px-10 lg:px-12 py-8 max-w-7xl min-h-screen flex flex-col">
    <!-- Header -->
    <div class="text-center mb-12">
      <h1 class="premium-title text-3xl sm:text-4xl md:text-5xl lg:text-6xl font-bold mb-4 glow-text">EC Selection Voting</h1>
      <p class="text-base sm:text-lg md:text-xl text-black font-medium">Profile of Three Candidates - Computer Technology Students</p>
    </div>

    <!-- Candidates -->
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8 justify-items-center">
      <!-- Candidate 1 -->
      <div class="candidate-card rounded-2xl p-6">
        <img src="https://iili.io/FNpupix.md.jpg" alt="Min Htaw Lwe" class="w-full h-56 object-cover rounded-xl mb-4">
        <h3 class="text-xl sm:text-2xl font-bold text-black">Min Htaw Lwe (ML)</h3>
        <p class="text-black text-sm sm:text-base font-semibold mb-3">UCSTT(19-20)-001</p>
        <p class="text-black text-sm leading-relaxed mb-3">Dedicated Computer Technology student with strong academic performance and leadership potential.</p>
      </div>

      <!-- Candidate 2 -->
      <div class="candidate-card rounded-2xl p-6">
        <img src="https://iili.io/FNpdvjt.md.jpg" alt="Tin Myo Zin Nwe" class="w-full h-56 object-cover rounded-xl mb-4">
        <h3 class="text-xl sm:text-2xl font-bold text-black">Tin Myo Zin Nwe (TN)</h3>
        <p class="text-black text-sm sm:text-base font-semibold mb-3">UCSTT(19-20)-041</p>
        <p class="text-black text-sm leading-relaxed mb-3">Enthusiastic Computer Technology student with excellent communication skills and collaborative approach.</p>
      </div>

      <!-- Candidate 3 -->
      <div class="candidate-card rounded-2xl p-6">
        <img src="./girl.JPG" alt="Wai Wai Aung" class="w-full h-56 object-cover rounded-xl mb-4">
        <h3 class="text-xl sm:text-2xl font-bold text-black">Wai Wai Aung (WA)</h3>
        <p class="text-black text-sm sm:text-base font-semibold mb-3">UCSTT(19-20)-087</p>
        <p class="text-black text-sm leading-relaxed mb-3">Motivated Computer Technology student with creative problem-solving abilities.</p>
      </div>
      
    </div>

    <!-- Footer -->
    <div class="text-center mt-12">
      <p class="text-black text-sm sm:text-lg font-semibold">EC SELECTION VOTING • 2025</p>
      <div class="flex items-center justify-center space-x-4 text-xs sm:text-sm text-black mt-4">
        <span>🎓 Education</span>
        <span>•</span>
        <span>💻 Technology</span>
        <span>•</span>
        <span>🚀 Innovation</span>
      </div>
    </div>
  </div>
</body>
</html>




