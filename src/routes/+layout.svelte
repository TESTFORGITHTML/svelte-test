<nav>
<div class="nav-container">
<a href="/" class="nav-logo" title="Back to Homepage">Имя Фамилия</a>
<div class="nav-links">
<a href="/about" class="link">Обо мнe</a> 
<a href="/blog" class="link">Блoг</a>
<a href="/projects" class="link">Портфолио</a> 
<a href="/contact" class="link">Kонтакты</a>
</div>
</div> 
</nav>

<div class="container">
<!-- Pages will be injected below -->
<slot></slot>
</div>

<style>
.container {
max-width: 1400px;
margin: 50px auto;
}
</style>