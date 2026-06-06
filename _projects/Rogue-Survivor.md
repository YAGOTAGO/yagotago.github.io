---
title: Rogue Survivor
date: 2026-06-04 08:01:35 +0300
subtitle: 
image: '/images/rogue-survivor/survivor.gif'
---

## Play it in-browser below!

<iframe 
    src="https://tiagodavies.com/rogue-survivor/" 
    title="Rogue Survivor Game"
    loading="lazy" 
    frameborder="0" 
    class="game-iframe"
    allowfullscreen>
</iframe>

## Description

Rogue Survivor is a survivors like built with an ECS architecture. Currently a work in-progress.

## Tech Stack
* **Framework:** <a href="https://phaser.io/" target="_blank" rel="noopener noreferrer">Phaser 4.1</a> (WebGL/Canvas 2D Rendering)
* **ECS Framework:** <a href="https://github.com/NateTheGreatt/bitECS" target="_blank" rel="noopener noreferrer">bitECS</a>
* **Language:** ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff)
* **Tools:** ![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=fff) [![npm](https://img.shields.io/badge/npm-CB3837?logo=npm&logoColor=fff)](#), Tiled, <a href="https://www.npmjs.com/package/phaser3-rex-plugins" target="_blank" rel="noopener noreferrer">RexUI</a>
* **Art:** <a href="https://sethbb.itch.io/32rogues" target="_blank" rel="noopener noreferrer">32rogues</a>

## Architecture Highlights
* **Thousands of entities:** Testing showed stable framerate at over 2k entities
* **Cache Locality:** The ECS architecture stores all state in flat TypesArrays
* **Sprite Pooling:** Object pooling for sprites to reduce garbage collection and instancing
* **Spatial Hashing:** Custom collider system with spatial hashing to reduce collision checks allowing more entities to be in the world

## Code
<div class="social social--large">
  <ul class="social__list list-reset">
    <li class="social__item">
      <a class="social__link" href="https://github.com/YAGOTAGO/rogue-survivor/" target="_blank" rel="noopener"
        aria-label="GitHub"><i class="ion ion-logo-github"></i></a>
    </li>
  </ul>
</div>