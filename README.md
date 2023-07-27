Passando valores de responsividade para um componente

Também foi inserido no arquivo tailwind.confg.js o seguinte codigo:

```bash
safelist: [
    {
      pattern: /^grid-cols-/,
      variants: ['sm', 'md', 'lg', 'xl', '2xl'],
    },
  ],
```

