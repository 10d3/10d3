# Hey, I'm Rley 👋🏼

## A passionate full-stack developer

*Veni, vidi, codi*

### What I'm working on
- I'm currently working on [AlloBillet](https://github.com/10d3/maplas.git)
- I'm currently learning **Anything I find interesting**
- All of my projects are available at [my portfolio](https://amherley.vercel.app/) but it's not finished yet
- I regularly write articles on [my blog](https://amherley.vercel.app/blog)

### Ask me about
- React
- NextJS
- Django
- NodeJS
- TypeScript
- TailWindCss
- Python

### How to reach me
- **marcherleyantoine@gmail.com**

### Experiences
- Check out my experiences [here](https://herley.netlify.app/certificat.pdf)

### Fun fact
- I think I'm funny

```jsx
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

### Connect with me
<a href="https://linkedin.com/in/aherleym" target="blank">
  <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="aherleym" height="30" width="40" />
</a>

<p align="right">
  <img src="https://komarev.com/ghpvc/?username=10d3&label=Profile%20views&color=0e75b6&style=flat" alt="10d3" />
</p>
