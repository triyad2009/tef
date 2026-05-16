<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TASNIMUL EHSAN FAHAD</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&amp;family=Inter:wght@400;500;600&amp;display=swap');

        body {
            font-family: 'Inter', system-ui, sans-serif;
            background: #fff9f8;
        }

        .name-font {
            font-family: 'Playfair Display', serif;
        }

        .profile-container {
            position: relative;
            display: inline-block;
        }

        .profile-img {
            width: 240px;
            height: 240px;
            border: 12px solid #e11d48;
            border-radius: 9999px;
            object-fit: cover;
            box-shadow: 0 10px 40px rgba(225, 29, 72, 0.3);
        }

        .verified {
            position: absolute;
            bottom: 15px;
            right: 15px;
            background: #e11d48;
            color: white;
            width: 48px;
            height: 48px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            border: 4px solid white;
            box-shadow: 0 4px 15px rgba(0,0,0,0.15);
        }

        .social-btn {
            width: 62px;
            height: 62px;
            background: white;
            border-radius: 9999px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 28px;
            color: #e11d48;
            box-shadow: 0 5px 20px rgba(225, 29, 72, 0.15);
            transition: all 0.3s ease;
        }

        .social-btn:hover {
            transform: translateY(-6px);
            box-shadow: 0 10px 25px rgba(225, 29, 72, 0.25);
        }
    </style>
</head>
<body class="min-h-screen flex items-center justify-center p-6 overflow-hidden">

    <div class="text-center max-w-sm mx-auto">
        
        <!-- Profile -->
        <div class="profile-container mx-auto mb-8">
            <img 
                src="https://i.postimg.cc/k5GzGYgN/FB-IMG-1778864926760.jpg" 
                alt="TASNIMUL EHSAN FAHAD"
                class="profile-img"
            >
            <div class="verified">
                <i class="fa-solid fa-check text-2xl"></i>
            </div>
        </div>

        <!-- Name -->
        <h1 class="name-font text-5xl font-bold text-[#e11d48] tracking-tight mb-6">
            TASNIMUL EHSAN FAHAD
        </h1>

        <!-- Junior Executive -->
        <div class="inline-flex items-center gap-3 bg-[#e11d48] text-white text-lg font-semibold px-10 py-4 rounded-full shadow-xl mb-6">
            <span class="text-xl">⚡</span>
            JUNIOR EXECUTIVE
            <span class="text-xl">⚡</span>
        </div>

        <!-- Company -->
        <p class="text-zinc-700 text-2xl mb-12">
            at <span class="text-[#e11d48] font-semibold">Envobyte</span>
        </p>

        <!-- Social Icons -->
        <div class="flex justify-center gap-6 mb-8">
            <a href="#" class="social-btn"><i class="fa-brands fa-facebook-f"></i></a>
            <a href="#" class="social-btn"><i class="fa-brands fa-instagram"></i></a>
            <a href="#" class="social-btn"><i class="fa-brands fa-linkedin-in"></i></a>
            <a href="#" class="social-btn"><i class="fa-brands fa-x-twitter"></i></a>
        </div>

        <!-- Email -->
        <div class="flex justify-center mb-12">
            <a href="#" class="social-btn text-3xl">
                <i class="fa-solid fa-envelope"></i>
            </a>
        </div>

        <!-- Bottom Divider -->
        <div class="flex items-center justify-center gap-4">
            <div class="h-px w-24 bg-rose-300"></div>
            <div class="text-4xl text-[#e11d48]">★</div>
            <div class="h-px w-24 bg-rose-300"></div>
        </div>

    </div>

</body>
</html>
