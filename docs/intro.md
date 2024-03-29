---
sidebar_position: 1
---

# Images

## MDX Image

## Centered

<figure style={{textAlign: 'center'}}>
  <img src={require('/img/docusaurus.png').default} />
</figure>

## Resized

<img src={require('/img/israel-pina.png').default} style={{width: '300px'}} />

### Resized+Centered

<figure style={{textAlign: 'center'}}>
  <img src={require('/img/israel-pina.png').default} style={{width: '400px'}} />
</figure>

### Resized+Centered+Http Link

<figure style={{textAlign: 'center'}}>
  <a href="https://news.ycombinator.com">
    <img
      src={require('/img/israel-pina.png').default}
      style={{width: '300px'}}
    />
  </a>
</figure>

### Resized+Centered+Relative link

<figure style={{textAlign: 'center'}}>
  <a href="./relative-images/examples">
    <img
      src={require('/img/israel-pina.png').default}
      style={{width: '300px'}}
    />
  </a>
</figure>

## Note on SVG

:::note

SVGs are always rendered as simple Markdown images, becauce the`  require().default  `syntax doesn't resolve svg's correctly. More work is needed to detect if image is `svg` and render it as inline `svg`.

:::

![](/img/logo.svg)

## Images rendered as simple Markdown

### Image with no attributes

![](/img/israel-pina.png)

### Image with link only

[![](/img/israel-pina.png)](https://news.ycombinator.com)
