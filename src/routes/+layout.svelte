<nav>
<div class="nav-container">
<a href="/" class="nav-logo" title="Back to Homepage">Имя Фамилия</a>
<div class="nav-links">
{#if link.isShow}

<a href={link.href} class="link">{link.title}</a>

{/if}
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

<script>
    const nav = [
    {
    title: 'Обо мнe',
    href: '/about',
    isShow: true,
    },
    {
    title: 'Блoг',
    href: '/blog',
    isShow: true,
    },
    {
    title: 'Портфолио',
    href: '/project',
    isShow: true,
    },
    {
    title: 'Контакты',
    href: '/contact',
    isShow: true,
    },
    {
    title: 'temp',
    href: '/temp',
    isShow: false,
    },
    ]
    </script>