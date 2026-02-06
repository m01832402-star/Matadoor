
<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>মাতাদোর ব্যালপেন লিঃ - চাকরির আবেদনপত্র</title>
    <style>
        body {
            font-family: 'Kalpurush', 'Siyam Rupali', Arial, sans-serif;
            background: #000000;
            color: #00ff00;
            margin: 0;
            padding: 20px;
            min-height: 100vh;
            overflow-x: hidden;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
            background: #000000;
            border: 2px solid #00ff00;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 0 40px rgba(0, 255, 0, 0.5);
            animation: slideDown 1.2s ease-out forwards;
            opacity: 0;
            transform: translateY(-50px);
        }
        @keyframes slideDown {
            to { opacity: 1; transform: translateY(0); }
        }
        h2 {
            text-align: center;
            color: #00ff00;
            font-size: 30px;
            text-shadow: 0 0 15px #00ff00;
            margin-bottom: 30px;
            animation: glowText 2s infinite alternate;
        }
        @keyframes glowText {
            from { text-shadow: 0 0 10px #00ff00; }
            to { text-shadow: 0 0 30px #00ff00, 0 0 40px #00ff00; }
        }
        .logo {
            text-align: center;
            margin-bottom: 25px;
            animation: fadeIn 1.5s ease-in 0.5s forwards;
            opacity: 0;
        }
        .logo img {
            width: 160px;
            border: 3px solid #00ff00;
            border-radius: 50%;
            padding: 8px;
            background: #000;
            box-shadow: 0 0 25px #00ff00;
        }
        @keyframes fadeIn {
            to { opacity: 1; }
        }
        label {
            display: block;
            margin: 18px 0 8px;
            font-weight: bold;
            color: #00ff00;
            text-shadow: 0 0 8px #00ff00;
            animation: labelFade 0.8s ease-out forwards;
            opacity: 0;
            transform: translateX(-30px);
        }
        input, select, textarea {
            width: 100%;
            padding: 14px;
            background: #000000;
            border: 2px solid #00ff00;
            border-radius: 10px;
            color: #00ff00;
            font-size: 16px;
            box-sizing: border-box;
            transition: all 0.4s ease;
        }
        input:focus, select:focus, textarea:focus {
            outline: none;
            border-color: #00ff00;
            box-shadow: 0 0 25px rgba(0, 255, 0, 0.9);
            transform: scale(1.02);
            animation: pulse 1.5s infinite;
        }
        @keyframes pulse {
            0% { box-shadow: 0 0 20px rgba(0, 255, 0, 0.7); }
            50% { box-shadow: 0 0 40px rgba(0, 255, 0, 1); }
            100% { box-shadow: 0 0 20px rgba(0, 255, 0, 0.7); }
        }
        ::placeholder { color: #006400; }
        .row { display: flex; gap: 15px; }
        .row > div { flex: 1; }
        button {
            margin-top: 35px;
            width: 100%;
            padding: 18px;
            background: #00ff00;
            color: #000;
            border: none;
            border-radius: 12px;
            font-size: 22px;
            font-weight: bold;
            cursor: pointer;
            box-shadow: 0 0 30px rgba(0, 255, 0, 0.7);
            transition: all 0.4s;
        }
        button:hover {
            transform: translateY(-5px);
            background: #00cc00;
            box-shadow: 0 0 50px rgba(0, 255, 0, 1);
        }
        .footer {
            text-align: center;
            margin-top: 50px;
            padding-top: 25px;
            border-top: 2px dashed #00ff00;
            color: #00ff00;
            font-size: 16px;
            text-shadow: 0 0 10px #00ff00;
        }
        .footer strong {
            font-size: 20px;
            color: #00ff00;
        }
        @media (max-width: 480px) { .row { flex-direction: column; } }
        label:nth-of-type(1) { animation-delay: 0.3s; }
        label:nth-of-type(2) { animation-delay: 0.5s; }
        label:nth-of-type(3) { animation-delay: 0.7s; }
        label:nth-of-type(4) { animation-delay: 0.9s; }
        label:nth-of-type(5) { animation-delay: 1.1s; }
        label:nth-of-type(6) { animation-delay: 1.3s; }
        label:nth-of-type(7) { animation-delay: 1.5s; }
        label:nth-of-type(8) { animation-delay: 1.7s; }
        label:nth-of-type(9) { animation-delay: 1.9s; }
        label:nth-of-type(10) { animation-delay: 2.1s; }
        @keyframes labelFade {
            to { opacity: 1; transform: translateX(0); }
        }
    </style>
    <link href="https://fonts.maateen.me/kalpurush/font.css" rel="stylesheet">
</head>
<body>

<div class="container">
    <div class="logo">
        <img src="https://i.postimg.cc/SxqKcGL7/grok-1765435026215.jpg" alt="Matador Ballpen Industries Ltd.">
    </div>
    
    <h2>চাকরির আবেদনপত্র</h2>
    
    <!-- এখানে আপনার Basin Endpoint বসানো হয়েছে -->
    <form action="https://usebasin.com/f/8b7a803a6901" method="POST" enctype="multipart/form-data">

        <label>পূর্ণ নাম *</label>
        <input type="text" name="পূর্ণ নাম" placeholder="তোমার পুরো নাম লেখো" required>

        <label>বাবার নাম *</label>
        <input type="text" name="বাবার নাম" placeholder="তোমার বাবার নাম লিখো" required>

        <label>মায়ের নাম *</label>
        <input type="text" name="মায়ের নাম" placeholder="তোমার মায়ের নাম লিখো" required>

        <label>মোবাইল নম্বর *</label>
        <input type="tel" name="মোবাইল নম্বর" placeholder="01xxxxxxxxx" required>

        <label>ইমেইল (যদি থাকে)</label>
        <input type="email" name="ইমেইল" placeholder="example@gmail.com">

        <div class="row">
            <div><label>বয়স *</label>
                <input type="number" name="বয়স" placeholder="25" required>
            </div>
            <div><label>লিঙ্গ *</label>
                <select name="লিঙ্গ" required>
                    <option value="">নির্বাচন করো</option>
                    <option value="পুরুষ">পুরুষ</option>
                    <option value="মহিলা">মহিলা</option>
                    <option value="অন্যান্য">অন্যান্য</option>
                </select>
            </div>
        </div>

        <label>বর্তমান ঠিকানা *</label>
        <textarea name="বর্তমান ঠিকানা" rows="3" placeholder="বিস্তারিত ঠিকানা লেখো" required></textarea>

        <label>পড়াশোনার যোগ্যতা *</label>
        <select name="পড়াশোনার যোগ্যতা" required>
            <option value="">নির্বাচন করো</option>
            <option>এসএসসি</option>
            <option>এইচএসসি</option>
            <option>স্নাতক</option>
            <option>স্নাতকোত্তর</option>
            <option>অন্যান্য</option>
        </select>

        <label>আইডি কার্ড অথবা জন্ম নিবন্ধন নম্বর *</label>
        <input type="text" name="আইডি কার্ড নম্বর" placeholder="যেমন: ১৯৯৯১২৩৪৫৬৭৮৯" required>

        <label>অভিজ্ঞতা (বছর)</label>
        <input type="number" name="অভিজ্ঞতা" placeholder="0 যদি না থাকে" min="0">

        <label>পাসপোর্ট সাইজ ছবি আপলোড *</label>
        <input type="file" name="ছবি" accept=".jpg,.jpeg,.png,.pdf">

        <label>আইডি কার্ড / জন্ম নিবন্ধনের ছবি *</label>
        <input type="file" name="আইডি ছবি" accept=".jpg,.jpeg,.png,.pdf">


        <label>টাকা পাঠানোর মোবাইল নম্বরের লাস্ট ৫ ডিজিট *</label>
                <strong>01993713203 Bkash/Nagad (parsonal)</strong>
                        <strong>আগে টাকা পাঠানোর পরে এখানে লাস্ট নাম্বার লিখে তারপরে সাবমিট করবেন অ্যাপ্লিকেশন</strong>
        <input type="text" name="টাকা পাঠানোর নম্বর" placeholder="যেমন: ৭১৩২০" maxlength="5" required>

        <button type="submit">আবেদন জমা দিন</button>
    </form>

    <div class="footer">
        <strong>Matador Ballpen Industries Ltd.</strong><br>
        ম্যাটাডোর হারবার (৯ম তলা), ভিকারুন্নেসা স্কুলের পাশে,<br>
        ১০২/আজিমপুর রোড, ঢাকা-১২০৫, বাংলাদেশ।<br><br>
        মোবাইল: ০১৯৯৩৭১৩২০৩ (ইমো, হোয়াটসঅ্যাপ)
    </div>
</div>

</body>
</html>
