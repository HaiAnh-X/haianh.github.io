---
layout: page
title: "Book"
permalink: /books/
---

Here is a curated list of books and textbook chapters that I've read for improving myself.

<style>
  .book-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(210px, 1fr));
    gap: 1.5rem;
    margin: 1.5rem 0 2.5rem;
  }

  .book-card {
    display: flex;
    flex-direction: column;
    background: #ffffff;
    border: 1px solid #e1e4e8;
    border-radius: 10px;
    overflow: hidden;
    transition: transform 0.25s ease, box-shadow 0.25s ease, border-color 0.25s ease;
  }

  .book-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 10px 22px rgba(0, 0, 0, 0.08);
    border-color: #cbd5e1;
  }

  .book-cover-wrap {
    width: 100%;
    height: 250px;
    background: #f8fafc;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 14px;
    box-sizing: border-box;
    border-bottom: 1px solid #f1f5f9;
  }

  .book-cover {
    max-width: 100%;
    max-height: 100%;
    width: auto;
    height: auto;
    object-fit: contain;
    border-radius: 4px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.12);
    transition: transform 0.25s ease, box-shadow 0.25s ease;
  }

  .book-card:hover .book-cover {
    transform: scale(1.03);
    box-shadow: 0 6px 14px rgba(0, 0, 0, 0.16);
  }

  .book-info {
    padding: 1rem;
    display: flex;
    flex-direction: column;
    flex-grow: 1;
  }

  .book-title {
    font-size: 0.98rem;
    font-weight: 600;
    line-height: 1.35;
    margin: 0 0 0.35rem 0;
    color: #1e293b;
  }

  .book-author {
    font-size: 0.85rem;
    color: #64748b;
    margin: 0 0 0.85rem 0;
    line-height: 1.4;
  }

  .book-review {
    margin-top: auto;
    font-size: 0.82rem;
    padding: 0.45rem 0.65rem;
    background: #f8fafc;
    border-radius: 6px;
    border-left: 3px solid #22c55e;
    color: #334155;
    line-height: 1.4;
  }

  .review-label {
    font-weight: 600;
    color: #0f172a;
    margin-right: 0.25rem;
  }

  /* Dark mode compatibility with Minima auto skin */
  @media (prefers-color-scheme: dark) {
    .book-card {
      background: #161b22;
      border-color: #30363d;
    }
    .book-card:hover {
      box-shadow: 0 10px 24px rgba(0, 0, 0, 0.5);
      border-color: #58a6ff;
    }
    .book-cover-wrap {
      background: #0d1117;
      border-bottom-color: #21262d;
    }
    .book-title {
      color: #f0f6fc;
    }
    .book-author {
      color: #8b949e;
    }
    .book-review {
      background: #21262d;
      border-left-color: #2ea043;
      color: #c9d1d9;
    }
    .review-label {
      color: #f0f6fc;
    }
  }

  @media (max-width: 600px) {
    .book-grid {
      grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
      gap: 1rem;
    }
    .book-cover-wrap {
      height: 190px;
      padding: 10px;
    }
    .book-title {
      font-size: 0.9rem;
    }
    .book-author {
      font-size: 0.78rem;
    }
    .book-review {
      font-size: 0.75rem;
      padding: 0.35rem 0.5rem;
    }
  }
</style>

## Technical & Scientific Books

<div class="book-grid">
  <div class="book-card">
    <div class="book-cover-wrap">
      <img class="book-cover" src="{{ '/assets/books/tensor-decompositions.png' | relative_url }}" alt="Tensor Decompositions for Data Science" loading="lazy">
    </div>
    <div class="book-info">
      <h3 class="book-title">Tensor Decompositions for Data Science</h3>
      <p class="book-author">Grey Ballard, Tamara G. Kolda</p>
      <div class="book-review">
        <span class="review-label">Review:</span> G.O.A.T
      </div>
    </div>
  </div>

  <div class="book-card">
    <div class="book-cover-wrap">
      <img class="book-cover" src="{{ '/assets/books/information-theory.jpg' | relative_url }}" alt="Elements of Information Theory" loading="lazy">
    </div>
    <div class="book-info">
      <h3 class="book-title">Elements of Information Theory</h3>
      <p class="book-author">Thomas M. Cover, Joy A. Thomas</p>
      <div class="book-review">
        <span class="review-label">Review:</span> Classic, Respectful
      </div>
    </div>
  </div>

  <div class="book-card">
    <div class="book-cover-wrap">
      <img class="book-cover" src="{{ '/assets/books/convex-optimization.jpg' | relative_url }}" alt="Convex Optimization" loading="lazy">
    </div>
    <div class="book-info">
      <h3 class="book-title">Convex Optimization</h3>
      <p class="book-author">Stephen Boyd and Lieven Vandenberghe</p>
      <div class="book-review">
        <span class="review-label">Review:</span> Timeless
      </div>
    </div>
  </div>

  <div class="book-card">
    <div class="book-cover-wrap">
      <img class="book-cover" src="{{ '/assets/books/signal-processing.jpg' | relative_url }}" alt="Academic Press Library in Signal Processing Series" loading="lazy">
    </div>
    <div class="book-info">
      <h3 class="book-title">Academic Press Library in Signal Processing Series</h3>
      <p class="book-author">Elsevier</p>
      <div class="book-review">
        <span class="review-label">Review:</span> Everything you need for an EE diploma.
      </div>
    </div>
  </div>
</div>

## Other Skills

<div class="book-grid">
  <div class="book-card">
    <div class="book-cover-wrap">
      <img class="book-cover" src="{{ '/assets/books/methods-of-persuasion.jpg' | relative_url }}" alt="Methods of Persuasion" loading="lazy">
    </div>
    <div class="book-info">
      <h3 class="book-title">Methods of Persuasion</h3>
      <p class="book-author">Nick Kolenda</p>
      <div class="book-review">
        <span class="review-label">Review:</span> Teached me a lot
      </div>
    </div>
  </div>

  <div class="book-card">
    <div class="book-cover-wrap">
      <img class="book-cover" src="{{ '/assets/books/intro-psychology.jpg' | relative_url }}" alt="Introduction to PSYCHOLOGY" loading="lazy">
    </div>
    <div class="book-info">
      <h3 class="book-title">Introduction to PSYCHOLOGY</h3>
      <p class="book-author">Charles Stangor</p>
      <div class="book-review">
        <span class="review-label">Review:</span> Breakdown yourself
      </div>
    </div>
  </div>
</div>

---
