---
layout: page
title: "Book"
permalink: /books/
---

Here is a curated list of books and textbook chapters that I've studied.

<style>
  .book-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
    gap: 2rem 1.5rem;
    margin: 1.5rem 0 2.5rem;
  }

  .book-card {
    display: flex;
    flex-direction: column;
  }

  .book-cover-wrap {
    width: 100%;
    height: 240px;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 0.75rem;
  }

  .book-cover-wrap a {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    height: 100%;
  }

  .book-cover {
    max-width: 100%;
    max-height: 100%;
    width: auto;
    height: auto;
    object-fit: contain;
    border-radius: 3px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.15);
    transition: opacity 0.2s ease;
  }

  .book-cover-wrap a:hover .book-cover {
    opacity: 0.9;
  }

  .book-info {
    display: flex;
    flex-direction: column;
  }

  .book-title {
    font-size: 0.95rem;
    font-weight: 600;
    line-height: 1.35;
    margin: 0 0 0.3rem 0;
  }

  .book-title a {
    color: inherit;
    text-decoration: none;
  }

  .book-title a:hover {
    text-decoration: underline;
  }

  .book-author {
    font-size: 0.84rem;
    color: #666;
    margin: 0;
    line-height: 1.35;
  }

  @media (prefers-color-scheme: dark) {
    .book-author {
      color: #9da5b4;
    }
    .book-cover {
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.4);
    }
  }

  @media (max-width: 600px) {
    .book-grid {
      grid-template-columns: repeat(auto-fill, minmax(140px, 1fr));
      gap: 1.5rem 1rem;
    }
    .book-cover-wrap {
      height: 190px;
    }
  }
</style>

## Technical & Scientific Books

<div class="book-grid">
  <div class="book-card">
    <div class="book-cover-wrap">
      <a href="https://www.wiley.com/en-us/Elements+of+Information+Theory%2C+2nd+Edition-p-9780471241959" target="_blank" rel="noopener">
        <img class="book-cover" src="{{ '/assets/books/information-theory.jpg' | relative_url }}" alt="Elements of Information Theory" loading="lazy">
      </a>
    </div>
    <div class="book-info">
      <h3 class="book-title"><a href="https://www.wiley.com/en-us/Elements+of+Information+Theory%2C+2nd+Edition-p-9780471241959" target="_blank" rel="noopener">Elements of Information Theory</a></h3>
      <p class="book-author">Thomas M. Cover, Joy A. Thomas</p>
    </div>
  </div>

  <div class="book-card">
    <div class="book-cover-wrap">
      <a href="https://web.stanford.edu/~boyd/cvxbook/" target="_blank" rel="noopener">
        <img class="book-cover" src="{{ '/assets/books/convex-optimization.jpg' | relative_url }}" alt="Convex Optimization" loading="lazy">
      </a>
    </div>
    <div class="book-info">
      <h3 class="book-title"><a href="https://web.stanford.edu/~boyd/cvxbook/" target="_blank" rel="noopener">Convex Optimization</a></h3>
      <p class="book-author">Stephen Boyd and Lieven Vandenberghe</p>
    </div>
  </div>

  <div class="book-card">
    <div class="book-cover-wrap">
      <a href="https://services.math.duke.edu/~rtd/PTE/PTE5_011119.pdf" target="_blank" rel="noopener">
        <img class="book-cover" src="{{ '/assets/books/probability-durrett.jpg' | relative_url }}" alt="Probability: Theory and Examples" loading="lazy">
      </a>
    </div>
    <div class="book-info">
      <h3 class="book-title"><a href="https://services.math.duke.edu/~rtd/PTE/PTE5_011119.pdf" target="_blank" rel="noopener">Probability: Theory and Examples</a></h3>
      <p class="book-author">Rick Durrett</p>
    </div>
  </div>

  <div class="book-card">
    <div class="book-cover-wrap">
      <a href="https://cs.nyu.edu/~mohri/mlbook/" target="_blank" rel="noopener">
        <img class="book-cover" src="{{ '/assets/books/foundations-of-ml.jpg' | relative_url }}" alt="Foundations of Machine Learning" loading="lazy">
      </a>
    </div>
    <div class="book-info">
      <h3 class="book-title"><a href="https://cs.nyu.edu/~mohri/mlbook/" target="_blank" rel="noopener">Foundations of Machine Learning</a></h3>
      <p class="book-author">Mehryar Mohri, Afshin Rostamizadeh, Ameet Talwalkar</p>
    </div>
  </div>

  <div class="book-card">
    <div class="book-cover-wrap">
      <a href="https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/" target="_blank" rel="noopener">
        <img class="book-cover" src="{{ '/assets/books/understanding-ml.jpg' | relative_url }}" alt="Understanding Machine Learning: From Theory to Algorithms" loading="lazy">
      </a>
    </div>
    <div class="book-info">
      <h3 class="book-title"><a href="https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/" target="_blank" rel="noopener">Understanding Machine Learning: From Theory to Algorithms</a></h3>
      <p class="book-author">Shai Shalev-Shwartz, Shai Ben-David</p>
    </div>
  </div>

  <div class="book-card">
    <div class="book-cover-wrap">
      <a href="https://crypto.stanford.edu/~dabo/cryptobook/BonehShoup_0_6.pdf" target="_blank" rel="noopener">
        <img class="book-cover" src="{{ '/assets/books/applied-cryptography.jpg' | relative_url }}" alt="A Graduate Course in Applied Cryptography" loading="lazy">
      </a>
    </div>
    <div class="book-info">
      <h3 class="book-title"><a href="https://crypto.stanford.edu/~dabo/cryptobook/BonehShoup_0_6.pdf" target="_blank" rel="noopener">A Graduate Course in Applied Cryptography</a></h3>
      <p class="book-author">Dan Boneh and Victor Shoup</p>
    </div>
  </div>

  <div class="book-card">
    <div class="book-cover-wrap">
      <a href="https://www.cambridge.org/core/books/a-foundation-in-digital-communication/7B066E02580798C0B29A6487E604F4C2" target="_blank" rel="noopener">
        <img class="book-cover" src="{{ '/assets/books/digital-communication.jpg' | relative_url }}" alt="A Foundation in Digital Communication" loading="lazy">
      </a>
    </div>
    <div class="book-info">
      <h3 class="book-title"><a href="https://www.cambridge.org/core/books/a-foundation-in-digital-communication/7B066E02580798C0B29A6487E604F4C2" target="_blank" rel="noopener">A Foundation in Digital Communication</a></h3>
      <p class="book-author">Amos Lapidoth</p>
    </div>
  </div>
</div>

## Other Skills

<div class="book-grid">
  <div class="book-card">
    <div class="book-cover-wrap">
      <a href="https://www.kolenda.io/books/methods-of-persuasion" target="_blank" rel="noopener">
        <img class="book-cover" src="{{ '/assets/books/methods-of-persuasion.jpg' | relative_url }}" alt="Methods of Persuasion" loading="lazy">
      </a>
    </div>
    <div class="book-info">
      <h3 class="book-title"><a href="https://www.kolenda.io/books/methods-of-persuasion" target="_blank" rel="noopener">Methods of Persuasion</a></h3>
      <p class="book-author">Nick Kolenda</p>
    </div>
  </div>

  <div class="book-card">
    <div class="book-cover-wrap">
      <a href="https://www.penguin.co.uk/books/314162/the-dawn-of-everything-by-wengrow-david-graeber-and-david/9780141991061" target="_blank" rel="noopener">
        <img class="book-cover" src="{{ '/assets/books/dawn-of-everything.jpg' | relative_url }}" alt="The Dawn of Everything" loading="lazy">
      </a>
    </div>
    <div class="book-info">
      <h3 class="book-title"><a href="https://www.penguin.co.uk/books/314162/the-dawn-of-everything-by-wengrow-david-graeber-and-david/9780141991061" target="_blank" rel="noopener">The Dawn of Everything</a></h3>
      <p class="book-author">David Graeber and David Wengrow</p>
    </div>
  </div>
</div>

---
