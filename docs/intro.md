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

### Resized+Centered+relative link

<figure style={{textAlign: 'center'}}>
  <a href="./relative-images/relative-images">
    <img
      src={require('/img/israel-pina.png').default}
      style={{width: '300px'}}
    />
  </a>
</figure>
