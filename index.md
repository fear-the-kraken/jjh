---
layout: default
title: Collapsible Demo
---

# Demo: Collapsible with Image + Text

<details open>
  <summary>Example section (image left, text right)</summary>
  <div class="panel">
    <div class="row">
      <figure class="media">
        <img src="ipo_underpricing.png" alt="Example image" />
        <figcaption>Optional caption for the image.</figcaption>
      </figure>
      <div class="text">
        <p><strong>Side-by-side content inside a collapsible.</strong> This layout uses standard HTML
        <code>&lt;details&gt;</code>/<code>&lt;summary&gt;</code> plus a flexbox row to place an image next to rich text.</p>
        <p>Add any Markdown or HTML here—links, lists, additional images, even tables.</p>
        <p>Example link style: <a href="https://example.com">Visit example.com</a></p>
      </div>
    </div>
  </div>
</details>

<details>
  <summary>Image on the right (swap column order)</summary>
  <div class="panel">
    <div class="row">
      <div class="text">
        <p>Put the text column first and the image column second to flip the visual order.</p>
        <ul>
          <li>Keyboard accessible</li>
          <li>Mobile-friendly: columns stack automatically</li>
          <li>No JavaScript needed</li>
        </ul>
      </div>
      <figure class="media">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6e/Golde33443.jpg/480px-Golde33443.jpg" alt="Another example image" />
        <figcaption>Another optional caption.</figcaption>
      </figure>
    </div>
  </div>
</details>

<details>
  <summary>Multiple rows in one panel</summary>
  <div class="panel">
    <div class="row">
      <figure class="media">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f9/Moraine_Lake_17092005.jpg/480px-Moraine_Lake_17092005.jpg" alt="Third example image" />
      </figure>
      <div class="text">
        <p>You can stack additional rows by repeating the <code>.row</code> block.</p>
      </div>
    </div>
    <div class="row">
      <figure class="media">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/44/GoldenGateBridge-001.jpg/480px-GoldenGateBridge-001.jpg" alt="Fourth example image" />
      </figure>
      <div class="text">
        <p>Each row remains responsive and will stack on narrow screens.</p>
      </div>
    </div>
  </div>
</details>
