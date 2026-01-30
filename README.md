<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MusicFlow - 音乐人发行后台</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    
    <style>
        body { font-family: 'Inter', sans-serif; }
        .gradient-text {
            background: linear-gradient(to right, #818cf8, #c084fc);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
    </style>
</head>
<body class="bg-gray-900 text-white">

    <div class="flex h-screen overflow-hidden">

        <aside class="w-64 bg-gray-800 border-r border-gray-700 hidden md:flex flex-col">
            <div class="h-16 flex items-center px-8 border-b border-gray-700">
                <i class="fa-solid fa-record-vinyl text-indigo-500 text-2xl mr-3"></i>
                <span class="text-xl font-bold tracking-wider">MusicFlow</span>
            </div>
            
            <nav class="flex-1 px-4 py-6 space-y-2">
                <a href="#" class="flex items-center px-4 py-3 bg-indigo-600 text-white rounded-lg transition-colors">
                    <i class="fa-solid fa-chart-line w-6"></i>
                    <span class="font-medium">概览 (Overview)</span>
                </a>
                <a href="#" class="flex items-center px-4 py-3 text-gray-400 hover:bg-gray-700 hover:text-white rounded-lg transition-colors">
                    <i class="fa-solid fa-music w-6"></i>
                    <span class="font-medium">我的音乐</span>
                </a>
                <a href="#" class="flex items-center px-4 py-3 text-gray-400 hover:bg-gray-700 hover:text-white rounded-lg transition-colors">
                    <i class="fa-solid fa-wallet w-6"></i>
                    <span class="font-medium">版税结算</span>
                </a>
                <a href="#" class="flex items-center px-4 py-3 text-gray-400 hover:bg-gray-700 hover:text-white rounded-lg transition-colors">
                    <i class="fa-solid fa-bullhorn w-6"></i>
                    <span class="font-medium">推广工具</span>
                </a>
            </nav>

            <div class="p-4 border-t border-gray-700">
                <a href="#" class="flex items-center gap-3">
                    <img src="https://i.pravatar.cc/150?img=11" alt="Avatar" class="w-10 h-10 rounded-full border-2 border-indigo-500">
                    <div>
                        <p class="text-sm font-semibold">独立乐队 A</p>
                        <p class="text-xs text-gray-400">Pro 账户</p>
                    </div>
                </a>
            </div>
        </aside>

        <main class="flex-1 flex flex-col overflow-y-auto bg-gray-900">
            
            <header class="h-16 bg-gray-800 border-b border-gray-700 flex items-center justify-between px-8 sticky top-0 z-10">
                <h2 class="text-xl font-semibold">仪表盘</h2>
                <button class="bg-gradient-to-r from-indigo-500 to-purple-600 hover:from-indigo-600 hover:to-purple-700 text-white px-6 py-2 rounded-full font-medium shadow-lg transition-transform transform hover:scale-105 flex items-center gap-2">
                    <i class="fa-solid fa-cloud-arrow-up"></i>
                    发布新单曲
                </button>
            </header>

            <div class="p-8 space-y-8">
                
                <div>
                    <h1 class="text-3xl font-bold mb-2">早安, <span class="gradient-text">独立乐队 A</span></h1>
                    <p class="text-gray-400">你的音乐正在全球 150+ 平台播放。</p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="bg-gray-800 p-6 rounded-xl border border-gray-700 hover:border-indigo-500 transition-colors">
                        <div class="flex justify-between items-start mb-4">
                            <div>
                                <p class="text-gray-400 text-sm font-medium">累计版税 (Total Earnings)</p>
                                <h3 class="text-3xl font-bold mt-1">$1,240.50</h3>
                            </div>
                            <div class="p-2 bg-green-500/20 rounded-lg text-green-400">
                                <i class="fa-solid fa-dollar-sign"></i>
                            </div>
                        </div>
                        <p class="text-xs text-green-400 flex items-center gap-1">
                            <i class="fa-solid fa-arrow-trend-up"></i> +12.5% 较上月
                        </p>
                    </div>

                    <div class="bg-gray-800 p-6 rounded-xl border border-gray-700 hover:border-indigo-500 transition-colors">
                        <div class="flex justify-between items-start m# Dashboard
