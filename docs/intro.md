---
sidebar_position: 1
---

# Images x

## A simple image without attributes

![](/img/docusaurus.png)

## A centered image

<figure style={{textAlign: 'center'}}>
  <img src={require('/img/docusaurus.png').default} />
</figure>

## Image image with width

<img src={require('/img/docusaurus.png').default} style={{width: '300px'}} />

Relative image
