---
title: "Contact"
description: "Contact Form"
date: 2019-02-30
aliases: ["contact"]
author: "Programmer"
---

{{< rawhtml >}}

<div class="content">
    <p class="mb-2">To contact, please fill out the form below. Feel free to contant for any matter! Always interested to discuss, exchange point of views, all opinions are welcome!</p>
    <form name=contact action="https://getform.io/f/d3be8696-c0a7-4315-bf23-fd4bce295a4a" method=post>
    <div class="mb-4">
         <input type=text placeholder="Your Name" name=name class="w-full p-4 bg-gray-200 border border-gray-200 focus:outline-none focus:bg-white focus:border-gray-500 dark:bg-warmgray-700 dark:border-warmgray-700 dark:focus:bg-warmgray-800" required>
    </div>
    <div class="mb-4">
        <input type=text placeholder="Email Address" name=mail class="w-full p-4 bg-gray-200 border border-gray-200 focus:outline-none focus:bg-white focus:border-gray-500 dark:bg-warmgray-700 dark:border-warmgray-700 dark:focus:bg-warmgray-800" required>
    </div>
    <div class="mb-4">
        <input type=text placeholder="Subject" name=title class="w-full p-4 bg-gray-200 border border-gray-200 focus:outline-none focus:bg-white focus:border-gray-500 dark:bg-warmgray-700 dark:border-warmgray-700 dark:focus:bg-warmgray-800" required>
    </div>
    <div class="mb-4">
        <textarea rows=5 cols=30 placeholder="Message" name=message class="w-full p-4 bg-gray-200 border border-gray-200 focus:outline-none focus:bg-white focus:border-gray-500 dark:bg-warmgray-700 dark:border-warmgray-700 dark:focus:bg-warmgray-800" required></textarea>
    </div>
    <input type=submit value="Submit" class="w-full button duration-100 py-2 bg-gray-800 text-white cursor-pointer transition-colors hover:bg-gray-600">
    </form>
</div>
{{< /rawhtml >}}
