---
layout: default
title: Pantry Pals
---

# Pantry Pals

## Table of Contents
1. [Overview](#overview)
2. [Deployment](#deployment)
3. [Team Contract](#team-contract)
4. [User Guide](#user-guide)
5. [Developer Guide](#developer-guide)
6. [Screenshots](#screenshots)

<!--
comment out add in later as we progress through project
* [User Guide](#user-guide)
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
* [Development History](#development-history)
* [Continuous Integration](#continuous-integration)
* [Walkthrough videos](#walkthrough-videos)
* [Example enhancements](#example-enhancements)
* [Team](#team)
-->

---

## Overview

### Problem

### Approach

### Use Case Ideas

### Beyond the Basics

---

## Deployment

---

## Team Contract
[Link to Team Contract](https://docs.google.com/document/d/1QSisK4_q7C7179ZbYHU2LISKLjH-Tgl0kmKb8poIX38/edit?usp=sharing)

<!-- PDF.js settings -->
<div id="pdf-viewer" style="
    max-width:900px;
    margin:20px auto;
    border:1px solid #ccc;
    border-radius:8px;
    box-shadow:0 4px 10px rgba(0,0,0,0.1);
    overflow-y:auto;
    height:800px;
    background-color:white;
    padding:10px;
"></div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/pdf.js/3.11.174/pdf.min.js"></script>
<script>
const url = '/assets/team-contract.pdf';
const container = document.getElementById('pdf-viewer');

pdfjsLib.getDocument(url).promise.then(pdf => {
  for (let i = 1; i <= pdf.numPages; i++) {
    pdf.getPage(i).then(page => {
      const scale = 1.5;
      const viewport = page.getViewport({ scale });
      const canvas = document.createElement('canvas');
      const ctx = canvas.getContext('2d');
      canvas.height = viewport.height;
      canvas.width = viewport.width;
      canvas.style.display = 'block';
      canvas.style.margin = '10px auto';
      container.appendChild(canvas);
      page.render({ canvasContext: ctx, viewport: viewport });
    });
  }
});
</script>

---

## User Guide
[Link to User Guide](#)

---

## Developer Guide

---

## Screenshots
