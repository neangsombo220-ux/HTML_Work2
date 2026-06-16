<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SABAY NEWS</title>
    <!-- Font Awesome Icons loaded once in the head -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    
    <style>
        /* Global Reset & Font */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Khmer OS Siem Reap", Arial, sans-serif;
        }

        /* Navbar Styling */
        .navbar {
            background: #e53935;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 70px;
        }

        .navbar ul {
            list-style: none;
            display: flex;
        }

        .navbar ul li {
            position: relative;
        }

        .navbar ul li a {
            display: block;
            color: white;
            text-decoration: none;
            padding: 22px 20px;
            font-size: 20px;
            transition: 0.3s;
        }

        .navbar ul li a:hover {
            background: #c62828;
        }

        .navbar ul li.active a {
            background: #b71c1c;
        }

        .home-icon {
            font-size: 24px;
        }

        /* Top Bar Styling */
        .top-bar {
            background: #f2f2f2;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            color: #999;
            font-size: 14px; /* Adjusted slightly cleaner for meta text */
        }

        .right {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .right a {
            text-decoration: none;
            color: #999;
        }

        .right a:hover {
            color: #666;
        }

        /* Centering the Main Content */
        .main-container {
            max-width: 800px;  /* Limits width for readability */
            margin: 0 auto;    /* Centers the entire block horizontally */
            padding: 20px;     /* Adds breathing room on small screens */
        }

        .article-title {
            text-align: center;
            margin: 30px 0;
            font-size: 28px;
            line-height: 1.5;
        }

        .content p {
            font-size: 18px;
            line-height: 1.8;
            margin-bottom: 20px;
            color: #333;
            text-align: justify; /* Looks cleaner for news articles */
        }

        .content img {
            width: 100%;       /* Makes images responsive */
            height: auto;
            margin: 15px 0 25px 0;
            border-radius: 4px; /* Optional: Softens image corners */
        }

        /* Related Tags Section */
        .related-tags {
            margin-top: 40px;
            border-top: 1px solid #eee;
            padding-top: 20px;
        }

        .related-tags p {
            font-size: 18px;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .button {
            background-color: #f2f2f2;
            border: none;
            color: #555;
            padding: 8px 16px;
            font-size: 14px;
            margin-right: 5px;
            cursor: pointer;
            border-radius: 4px;
            transition: 0.2s;
        }

        .button:hover {
            background-color: #e53935;
            color: white;
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <nav class="navbar">
        <ul>
            <li>
                <a href="#"><i class="fa-solid fa-house home-icon"></i></a>
            </li>
            <li><a href="#">សុខភាព</a></li>
            <li class="active"><a href="#">បច្ចេកវិទ្យា</a></li>
            <li><a href="#">អន្តរជាតិ</a></li>
            <li><a href="#">កីឡា</a></li>
            <li><a href="#">AUTO TALK</a></li>
        </ul>
    </nav>

    <!-- Top Meta Bar -->
    <div class="top-bar">
        <div class="left">
            ពុធ, 16 មិថុនា 2026 16:47
        </div>
        <div class="right">
            <i class="fa-solid fa-comment"></i>
            <a href="#">មតិយោបល់ 0</a>
            |
            <i class="fa-solid fa-comments"></i>
            <a href="#">មតិយោបល់ផ្សេងទៀត 0</a>
        </div>
    </div>

    <!-- Centered Content Wrapper -->
    <div class="main-container">
        
        <h2 class="article-title">Metfone ដាក់ចេញជាផ្លូវការនូវគម្រោងដាតាអ៊ីនធឺណិត 5G ល្បឿនលឿនថ្មី ដ៏ទាក់ទាញ</h2>

        <div class="content">
            <p>បន្ទាប់ពីការសាកល្បងបច្ចេកទេសរយៈពេលបីខែ និងលទ្ធផលដ៏ជោគជ័យ Metfone បានប្រកាសជាផ្លូវការនូវការដាក់ឱ្យដំណើរការពាណិជ្ជកម្មនៃគម្រោងដាតា 5G ថ្មី របស់ខ្លួនចាប់ពីថ្ងៃទី 1 ខែមេសា ឆ្នាំ 2026 តទៅ។</p>
            
            <img src="ssc.jpg" alt="Metfone 5G launch graphic showing a woman in a futuristic corridor with glowing city skyline and bold met5g text conveying high speed technology">
            
            <p>ក្នុងអំឡុងពេលដំណាក់កាលសាកល្បងចាប់ពីខែមករាដល់ខែមីនា ឆ្នាំ 2026 បណ្តាញ 5G របស់ Metfone បានបង្ហាញពីដំណើរការដែលមានស្ថេរភាព រួមជាមួយនឹងសមត្ថភាពបញ្ជូនទិន្នន័យល្បឿនលឿន។ ដោយផ្អែកលើមតិប្រតិកម្មវិជ្ជមានរបស់អ្នកប្រើប្រាស់ Metfone បានដាក់ចេញជាផ្លូវការជាមួយគម្រោងឈ្មោះថា “Met5G” ថ្មី ដែលផ្តល់នូវគុណសម្បត្តិសំខាន់ៗក្នុងបរិមាណទិន្នន័យដ៏គួរឱ្យទាក់ទាញ។</p>
            
            <p>ដើម្បីបំពេញតម្រូវការអតិថិជនចម្រុះ Metfone ផ្តល់ជូននូវ 5 គម្រោងដែលបត់បែនចាប់ពីជម្រើសរយៈពេលខ្លីរហូតដល់រយៈពេលវែង។ សម្រាប់ការប្រើប្រាស់ប្រចាំសប្តាហ៍ គម្រោង Met5G 1 និង Met5G 2 មានចាប់ពីតម្លៃត្រឹមតែ 1.5 ដុល្លារប៉ុននោះ ដែលសមស្របសម្រាប់ការចូលប្រើដែលមានតម្លៃសមរម្យ និងងាយស្រួល។ សម្រាប់អ្នកប្រើប្រាស់ដែលមានតម្រូវការច្រើន គម្រោងប្រចាំខែដូចជា Met5G 6 Met5G 10 និង Met5G 15 ផ្តល់ជូនទិន្នន័យរហូតដល់ 250GB រួមជាមួយនឹងនាទី សារ SMS ឥតគិតថ្លៃជាច្រើន។ ជាពិសេស គម្រោងទាំងអស់នេះ ក៏អាចប្រើប្រាស់បានជាមួយបណ្តាញ 4G ដែលធានាបាននូវការប្រើប្រាស់ដ៏រលូននៅទូទាំងតំបន់គ្របដណ្តប់។</p>
            
            <img src="tts.jpg" alt="Metfone 5G launch">
            
            <p>ជាមួយគម្រោង Met5G ថ្មី អ្នកប្រើប្រាស់មិនត្រឹមតែទទួលបានជម្រើសកាន់តែច្រើនប៉ុននោះទេ ប៉ុន្តែថែមទាំងរីករាយនឹងបទពិសោធន៍ឌីជីថលកាន់តែប្រសើរឡើងផងដែរ។ រាប់ចាប់ពីការចាក់វីដេអូ ការផ្សាយបន្តផ្ទាល់ និងការកម្សាន្ត រហូតដល់ការរៀនតាមអ៊ីនធឺណិត និងការងារពីចម្ងាយ សកម្មភាពទាំងអស់កាន់តែរលូន និងមានស្ថេរភាពជាងមុន។ ការផ្តល់ជូននូវទិន្នន័យធំៗទាំងនេះធានានូវការតភ្ជាប់ជាបន្តបន្ទាប់ ខណៈពេលដែលល្បឿនលឿនផ្តល់នូវបទពិសោធន៍ដ៏រលូន និងគ្មានការរំខាន។</p>
            
            <img src="ww.jpg" alt="Metfone 5G launch">
            
            <p>សម្រាប់ព័ត៌មានបន្ថែមអំពីគម្រោង Met5G និងតំបន់គ្របដណ្តប់សេវា 5G អតិថិជនអាចចូលទៅកាន់៖ <a href="https://metfone.com.kh/met5G">https://metfone.com.kh/met5G</a> ឬហាង Metfone ណាមួយនៅទូទាំងប្រទេស៕</p>
        </div>

        <!-- Related Tags Section -->
        <div class="related-tags">
            <p>ពាក្យទាក់ទង</p>
            <button class="button">ពត៏មាន</button>
            <button class="button">Sponsor</button>
        </div>

    </div>

</body>
</html>
