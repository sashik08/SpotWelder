<h1><a id="user-content-bluetooth-адресная-матрица-на-arduino" class="anchor" aria-hidden="true" href="#bluetooth-адресная-матрица-на-arduino"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Точечная сварка на Arduino</h1>
<article class="markdown-body entry-content container-lg" itemprop="text"><p><a target="_blank" rel="noopener noreferrer" href="https://github.com/HamsterTime-r/SpotWelder/blob/main/preview.jpg"><img src="https://raw.githubusercontent.com/HamsterTime-r/SpotWelder/main/preview.jpg" alt="PROJECT_PHOTO" style="max-width:100%;"></a></p>
<p><a id="user-content-chapter-0"></a></p>
<h2><a id="user-content-описание-проекта" class="anchor" aria-hidden="true" href="#описание-проекта"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Описание проекта</h2>
<p>Светильник на основе адресной светодиодной ленты с различными эффектами
Страница проекта на сайте: <a href="https://alexgyver.ru/gyverlight/" rel="nofollow">https://alexgyver.ru/gyverlight/</a></p>
<h4><a id="user-content-особенности" class="anchor" aria-hidden="true" href="#особенности"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Особенности:</h4>
<ul>
<li>Управление одним энкодером</li>
<li>Возможности:
<ul>
<li>Установка времени T1: предпрожига</li>
<li>Установка паузы P: между импульсами</li>
<li>Установка основного времени T2: прожига</li>
</ul>
</li>
<li>Управление:
<ul>
<li>1х нажатие энкодера - вход в меню</li>
<li>Прокруткой энкодера - выбираем нужное значение времени предпрожига T1:</li>
<li>1х нажатие энкодера - переходим на P:</li>
<li>Прокруткой энкодера - выбираем нужное значение паузы между импульсами P:</li>
<li>1х нажатие энкодера - переходим на T2:</li>
<li>Прокруткой энкодера - выбираем нужное значение времени основного прожига T2:</li>
</ul>
</li>
</ul>
<p><a id="user-content-chapter-1"></a></p>
<h2><a id="user-content-папки" class="anchor" aria-hidden="true" href="#папки"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Папки</h2>
<p><strong>ВНИМАНИЕ! Если это твой первый опыт работы с Arduino, читай <a href="#chapter-4">инструкцию</a></strong></p>
<ul>
<li><strong>libraries</strong> - библиотеки проекта. Заменить имеющиеся версии</li>
<li><strong>firmware</strong> - прошивки для Arduino</li>
<li><strong>schemes</strong> - схемы подключения компонентов</li>
</ul>
  <p><a id="user-content-chapter-2"></a></p>
<h2><a id="user-content-схемы" class="anchor" aria-hidden="true" href="#схемы"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Схемы</h2>
<p><a target="_blank" rel="noopener noreferrer" href="https://github.com/HamsterTime-r/SpotWelder/blob/main/schemes/scheme_1.jpg"><img src="https://github.com/AlexGyver/gyverlight/raw/master/schemes/scheme.jpg" alt="SCHEME" style="max-width:100%;"></a>
<a target="_blank" rel="noopener noreferrer" href="https://github.com/HamsterTime-r/SpotWelder/blob/main/schemes/scheme_1.jpg"><img src="https://github.com/AlexGyver/gyverlight/raw/master/schemes/scheme2.jpg" alt="SCHEME" style="max-width:100%;"></a></p>
<p><a id="user-content-chapter-3"></a></p>
