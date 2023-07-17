<script lang="ts">
    import '../app.scss';
    import Hero from '../components/Hero.svelte';
    import VSeparator from '../components/VSeparator.svelte';

    function who_am_i() {
        alert("I am Endercat!")
    }
</script>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />


<div class="nav">
    <div class="nav-left">
        <i class="fa fa-cat"></i> <i class="acc">Ender</i>cat
    </div>
    <div class="nav-right">
        <a href="#">Home</a>
        <a href="#">News</a>
        <a on:click={who_am_i}>About</a>
        <a href="mailto:blythinw@students.dsbn.org">Contact</a>
    </div>
</div>

<VSeparator/>

<div class="content">
    <Hero src="hero.jpg">
        <h1>Unemployment</h1>
    </Hero>
    <VSeparator/>
    <h1>What is unemployment?</h1>
    <p>Unemployment means that people need jobs and can't get them. This can happen either from jobs being unavailable, or from employers not offering good enough wages. Unemployment is a major issue because people need employment.</p>

    <h1>How might we lower the rate of unemployment and underemployment among Canadians?</h1>
    <p>The issue of unemployment and underemployment among Canadians is complex, and requires both short-term and long-term solutions. We can help fix it by creating job opportunities, improving skill development, and helping economic growth. This would require collaboration with the government, businesses, and schools to ensure that it benefits everyone.</p>
    
    <ol>
        <li>
            <h2>1. Enhancing skills and education</h2>
            <p>We can lower unemployment by improving education and training programs. This means providing more training and ensuring the skills being taught align with the needs of the job market.</p>
        </li>
        <li>
            <h2>2. Encouraging entrepreneurship</h2>
            <p>Supporting entrepreneurship can help create more jobs. We can do this by providing resources, mentorship, and financial assistance to aspiring entrepreneurs.</p>
        </li>
        <li>
            <h2>3. Promoting job creation</h2>
            <p>To lower unemployment, we need to focus on creating more job opportunities. This can be achieved through policies that incentivize businesses to expand and hire more workers. Examples include tax breaks or subsidies for companies that offer new jobs.</p>
        </li>
        <li>
            <h2>4. Investing in infrastructure and sustainable industries</h2>
            <p>Investing in infrastructure projects and emerging sustainable industries can have a positive impact on employment rates. By developing and maintaining infrastructure, we can create both short-term and long-term job opportunities.</p>
        </li>    
    </ol>

    <h1>Conclusion</h1>
    <p>To conclude, addressing the issue of unemployment and underemployment in Canada requires a complex approach with short-term and long-term solutions. By implementing strategies to enhance skills, entrepreneurship, promoting job creation, and investing in infrastructure and sustainability, we can work towards lower unemployment rates.</p> 
</div>