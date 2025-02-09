<h1> Homework </h1>
<h2> 1. Is Visual Studio 2022 better than Visual Studio Code? </h2>
<p> Нет, но есть ряды преимуществ у тех и других. Например: Легковестность и совместимость с ARM VS Code позволяет запускать на девайсах типа Raspberry Pi. Так же подходит для кроссплатформенной разработки. В то же время Visual Studio 2022 по большей части сделан для Windows и разработки на нем. В целом дело вкуса, IMO </p>
<h2> 2. Are .NET 5 and later better than .NET Framework? </h2>
<p> .NET Framework - легаси история, .NET 5 и выше объединили в себя все что было в .NET Framework. Хуже или лучше - нет ответа, важная штука для поддержания старыйх аппок, неиспользуемая в новых аппках. </p>
<h2> 3. What is .NET Standard and why is it still important? </h2>
<p> Спецификация для набора апишек, которые могут использовать .NET Core, .NET Framework и Xamarin для индикации совместимости. Устарела/устаревает в связи с единым .NET форматом  </p>
<h2> 4. Why can a programmer use different languages, for example, C# and F#, to write applications that run on .NET? </h2>
<p> Информация написанная с разных языков програмирования хранится в "assembly", поэтому это не имеет значения.  </p> 
<h2> 5. What is a top-level program and how do you access any command-line arguments? </h2>
<p> Фича, появившаяся в C#9, которая стала базовой для всех шаблонов проектов с C#10 и выше, которая автоматически испортит System в проект. Как получить доступ - При создании через флажки "Do not use top-level statements" в VS Studio и dotnet new console --use-program-main. Алсо, можно через throw new Exception();  </p>
<h2> 6. What is the name of the entry point method of a .NET console app and how should it be explicitly declared if you are not using the top-level program feature? </h2>
<p> method Main  </p>
<h2> 7. What namespace is the Program class defined in with a top-level program? </h2>
<p> HelloCS </p>
<h2> 8. Where would you look for help for a C# keyword? </h2>
<p> https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/ или если нужно разъяснение по кейворду - Show definition в VS Studio </p>
<h2> 9. Where would you look first for solutions to common programming problems? </h2>
<p> StackOverflow, Google </p>
<h2> 10. What should you do after getting an AI to write code for you? </h2>
<p> Перепроверить ~~или сжечь~~ . AI все еще хуево пишет код, нужно перепроверять, а вот получать советы по синтаксису и пр. норм </p>
<h2> 11. Как работает обратная совместимость в Dotnet? </h2>
<p> Через создание .NET Standard 2.0 библиотек </p>