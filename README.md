<img src="https://github.com/10d3/10d3/blob/7592e308043055570b8f0521c586493fbd6f2a5b/0d8c6a27b4b039d5b9cfe8aa4777766d.png" alt="aherleym" height="auto" width="100%" />

<h2 font-size='1.7rem'>Hey, I'm Rley 👋🏼</h3>
<h3 font-size="1.3rem" align="left">A passionate fullstack developer</h3>
<h3 font-size="1rem" align="left">Veni, vidi, codi</h3>

<h2 font-size=".7rem">What I am working on ?</h2>

- I’m currently working on [AlloBillet](https://github.com/10d3/maplas.git)
- I’m currently learning **Anything I find interesting**
- All of my projects are available at [my portfolio](https://amherley.vercel.app/) but it's not finished yet
- I regularly (not really) write articles on [herley.netlify.app/blog](https://amherley.vercel.app/blog)
- Ask me about **React, NextJS, Django, NodeJS, TypeScript, TailWindCss**
- How to reach me **marcherleyantoine@gmail.com**
- Know about my experiences [here](https://herley.netlify.app/certificat.pdf)
- I've already build my own NextJS Boilerplate
- Fun fact **I think I'm funny**


```JSX
  const plans = await stripe.plans.list({
    active: true,
  });


  for (const plan of plans.data) {
    await prisma.plan.upsert({
      where: {
        productPriceId: plan.id,
      },
      update: {
        productId: plan.product as string,
        price: plan.amount as number,
        interval: plan.interval,
        intervalCount: plan.interval_count,
      },
      create: {
        productPriceId: plan.id,
        productId: plan.product as string,
        price: plan.amount as number,
        interval: plan.interval,
        intervalCount: plan.interval_count,
      },
    });
  }
```


<h3 align="left">Connect with me:</h3>
<p align="left">
  <a href="https://linkedin.com/in/aherleym" target="blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="aherleym" height="30" width="40" />
  </a>
</p>


<p align="right">
  <img src="https://komarev.com/ghpvc/?username=10d3&label=Profile%20views&color=0e75b6&style=flat" alt="10d3" />
</p>
