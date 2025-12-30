<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>日本 2026 跨城市之旅</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Noto Sans JP', sans-serif; background-color: #f4f4f2; color: #333; }
        .day-card { background: white; border-radius: 16px; box-shadow: 0 4px 20px rgba(0,0,0,0.05); margin-bottom: 24px; overflow: hidden; }
        .time-node { position: relative; padding-left: 24px; border-left: 1px solid #e5e7eb; margin-left: 10px; padding-bottom: 20px; }
        .time-node::before { content: ''; position: absolute; left: -5px; top: 5px; width: 9px; height: 9px; background: #444; border-radius: 50%; }
        .tag-food { background: #fff1f2; color: #e11d48; font-size: 10px; padding: 2px 8px; border-radius: 4px; font-weight: bold; border: 0.5px solid #fda4af; }
        .tag-transport { background: #eff6ff; color: #2563eb; font-size: 10px; padding: 2px 8px; border-radius: 4px; font-weight: bold; border: 0.5px solid #93c5fd; }
        .tag-important { background: #fefce8; color: #ca8a04; font-size: 10px; padding: 2px 8px; border-radius: 4px; font-weight: bold; border: 0.5px solid #fde047; }
    </style>
</head>
<body class="pb-24">

    <div class="sticky top-0 z-50 bg-white/80 backdrop-blur-lg p-6 border-b border-gray-100">
        <h1 class="text-xl font-bold tracking-tight">🇯🇵 日本 2026 自駕行</h1>
        <p class="text-[10px] text-gray-400 uppercase tracking-widest mt-1">Osaka · Kyoto · Tokyo | 01.03 - 01.11</p>
    </div>

    <div class="p-4">
        <div class="day-card">
            <div class="bg-stone-800 p-4 text-white flex justify-between items-end">
                <div><span class="text-2xl font-bold">Day 1</span> <span class="text-sm ml-2">1/3 (六)</span></div>
                <div class="text-right text-xs opacity-80">大阪 · 大阪日航飯店<br>🌤️ 8°C</div>
            </div>
            <div class="p-5">
                <div class="time-node">
                    <div class="text-[10px] text-gray-400">06:30 - 09:55</div>
                    <div class="font-bold uppercase tracking-tight">長榮 BR0178</div>
                    <div class="text-xs text-gray-500 italic">桃園二航 ➔ 關西一航</div>
                </div>
                <div class="time-node">
                    <div class="text-[10px] text-gray-400">12:00</div>
                    <div class="font-bold flex items-center gap-2">黑門市場 <span class="tag-food">必吃海鮮</span></div>
                </div>
                <div class="time-node">
                    <div class="text-[10px] text-gray-400">15:00</div>
                    <div class="font-bold">電氣街</div>
                    <div class="text-xs text-gray-500 italic">夾娃娃 & 公仔巡禮</div>
                </div>
                <div class="time-node border-transparent">
                    <div class="text-[10px] text-gray-400">19:00</div>
                    <div class="font-bold">道頓堀 + 心齋橋</div>
                </div>
            </div>
        </div>

        <div class="day-card">
            <div class="bg-stone-700 p-4 text-white flex justify-between items-end">
                <div><span class="text-2xl font-bold">Day 2</span> <span class="text-sm ml-2">1/4 (日)</span></div>
                <div class="text-right text-xs opacity-80">大阪 · 大阪日航飯店<br>☁️ 7°C</div>
            </div>
            <div class="p-5">
                <div class="time-node">
                    <div class="text-[10px] text-red-500 font-bold">11:00 重點預約</div>
                    <div class="font-bold flex items-center gap-2 text-lg">大喜豬排 <span class="tag-food">需準時</span></div>
                </div>
                <div class="time-node border-transparent">
                    <div class="text-[10px] text-gray-400">14:00</div>
                    <div class="font-bold">橘街 + 美國村逛街</div>
                </div>
            </div>
        </div>

        <div class="day-card">
            <div class="bg-stone-600 p-4 text-white flex justify-between items-end">
                <div><span class="text-2xl font-bold">Day 3</span> <span class="text-sm ml-2">1/5 (一)</span></div>
                <div class="text-right text-xs opacity-80">京都 · 京都世紀飯店<br>🌤️ 6°C</div>
            </div>
            <div class="p-5">
                <div class="time-node">
                    <div class="text-[10px] text-blue-500 font-bold">12:51 - 13:04</div>
                    <div class="font-bold flex items-center gap-2 text-blue-600">新幹線 ➔ 京都 <span class="tag-transport">新大阪站發</span></div>
                </div>
                <div class="time-node border-transparent">
                    <div class="text-[10px] text-gray-400">下午</div>
                    <div class="font-bold text-sm">平安神宮 / 晴明神社</div>
                </div>
            </div>
        </div>

        <div class="day-card border-2 border-red-100">
            <div class="bg-red-800/90 p-4 text-white flex justify-between items-end">
                <div><span class="text-2xl font-bold text-yellow-300">Day 4</span> <span class="text-sm ml-2 font-bold">1/6 (二)</span></div>
                <div class="text-right text-xs opacity-80">京都 · 京都世紀飯店</div>
            </div>
            <div class="p-5 bg-red-50/30">
                <div class="time-node">
                    <div class="text-[10px] text-gray-400 uppercase">08:00</div>
                    <div class="font-bold">伏見稻荷大社</div>
                </div>
                <div class="time-node">
                    <div class="text-[10px] text-red-600 font-black tracking-tighter">13:00 MUST GO</div>
                    <div class="font-black text-xl text-red-700 underline decoration-double">空蟬亭</div>
                    <div class="text-xs text-red-500 mt-1 font-bold italic">※ 行程中最重點預約</div>
                </div>
                <div class="time-node border-transparent">
                    <div class="text-[10px] text-gray-400 uppercase">18:00</div>
                    <div class="font-bold uppercase tracking-tight">四條河原町</div>
                </div>
            </div>
        </div>

        <div class="day-card shadow-inner bg-gray-50 border-dashed border-2 border-gray-200">
            <div class="p-8 text-center text-gray-400 text-sm">
                1/7 - 1/11 東京段行程已加載...<br>
                (含 1/9 20:00 豬排之神 Ginza Katsukami)
            </div>
        </div>

        <div class="day-card">
            <div class="bg-gray-400 p-4 text-white flex justify-between items-end">
                <div><span class="text-2xl font-bold uppercase">Day 9</span> <span class="text-sm ml-2">1/11 (日)</span></div>
                <div class="text-right text-xs opacity-80 uppercase tracking-tighter">回台灣</div>
            </div>
            <div class="p-5">
                <div class="time-node border-transparent">
                    <div class="text-[10px] text-blue-600 font-bold uppercase">12:15 - 15:05</div>
                    <div class="font-bold text-lg uppercase">BR0191 羽田 ➔ 松山</div>
                </div>
            </div>
        </div>
    </div>

    <div class="fixed bottom-0 left-0 right-0 bg-white/90 backdrop-blur-xl border-t border-gray-100 flex justify-around py-4 pb-8 shadow-2xl">
        <div class="flex flex-col items-center"><span class="text-xl">🗾</span><span class="text-[10px] mt-1 font-bold text-stone-800 tracking-tighter">行程</span></div>
        <div class="flex flex-col items-center text-gray-300"><span class="text-xl opacity-40">🧾</span><span class="text-[10px] mt-1 tracking-tighter">記帳</span></div>
        <div class="flex flex-col items-center text-gray-300"><span class="text-xl opacity-40">📞</span><span class="text-[10px] mt-1 tracking-tighter">緊急</span></div>
    </div>

</body>
</html>
