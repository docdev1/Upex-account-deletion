
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Account & Data Deletion – Upex</title>
  <meta name="description" content="How to request deletion of your Upex account and associated personal data." />

  <style>
    :root {
      --max: 880px;
      --pad: 20px;
      --radius: 14px;
    }
    * { box-sizing: border-box; }
    body {
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, 'Helvetica Neue', Arial, 'Noto Sans', 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', sans-serif;
      line-height: 1.6;
      margin: 0;
      color: #111;
      background: #f7f7f8;
    }
    header {
      background: white;
      border-bottom: 1px solid #e5e7eb;
    }
    .wrap {
      max-width: var(--max);
      margin: 0 auto;
      padding: 24px var(--pad);
    }
    h1, h2 { line-height: 1.25; }
    .card {
      background: white;
      border: 1px solid #e5e7eb;
      border-radius: var(--radius);
      padding: 16px;
      margin: 16px 0;
    }
    .btn {
      display: inline-block;
      padding: 12px 16px;
      border-radius: 10px;
      border: 1px solid #111;
      text-decoration: none;
      font-weight: 600;
    }
    .muted { color: #4b5563; }
    footer {
      font-size: 14px;
      color: #6b7280;
      padding: 24px var(--pad) 48px;
      text-align: center;
    }
    ul { padding-left: 1.1rem; }
    code { background: #f3f4f6; padding: 2px 6px; border-radius: 6px; }
  </style>
</head>
<body>
  <header>
    <div class="wrap">
      <h1>Account & Data Deletion</h1>
      <p class="muted">This page explains how to delete your Upex account and associated personal data.</p>
    </div>
  </header>

  <main class="wrap" role="main">
    <section class="card" aria-labelledby="in-app">
      <h2 id="in-app">Delete your account in the app (recommended)</h2>
      <ol>
        <li>Open <strong>Upex</strong>.</li>
        <li>Go to <strong>Profile → Settings → Delete My Account</strong>.</li>
        <li>Confirm the deletion.</li>
      </ol>
      <p class="muted">If you no longer have the app or cannot sign in, use the email option below.</p>
    </section>

    <section class="card" aria-labelledby="email">
      <h2 id="email">Request deletion by email</h2>
      <p>Send an email from the address associated with your account to:</p>
      <p><a class="btn" href="mailto:medexamix@gmail.com?subject=Delete%20My%20Account%20-%20Upex">Email: medexamix@gmail.com</a></p>
      <p>Include the following:</p>
      <ul>
        <li>Subject: <code>Delete My Account - Upex</code></li>
        <li>Your account email: <code>medexamix@gmail.com</code> (if different from the sender)</li>
        <li>Optional: Any additional identifiers (User ID / phone) to help us locate your account</li>
      </ul>
    </section>

    <section class="card" aria-labelledby="what-we-delete">
      <h2 id="what-we-delete">What will be deleted</h2>
      <ul>
        <li>Your account profile (name, email, avatar)</li>
        <li>App-generated content associated with your account</li>
        <li>Analytics identifiers tied to your account</li>
      </ul>
      <p class="muted">Backups and logs are purged on a rolling basis within 30 days.</p>
    </section>

    <section class="card" aria-labelledby="what-we-may-keep">
      <h2 id="what-we-may-keep">What we may retain</h2>
      <p>We may retain minimal records if required to:</p>
      <ul>
        <li>Comply with legal obligations (e.g., fraud prevention, tax)</li>
        <li>Resolve disputes or enforce our terms</li>
      </ul>
      <p class="muted">Retained records are not used for any other purpose.</p>
    </section>

    <section class="card" aria-labelledby="timelines">
      <h2 id="timelines">How long it takes</h2>
      <ul>
        <li>In-app deletion: immediate sign-out and queuing for removal</li>
        <li>Email requests: acknowledgement within 72 hours</li>
        <li>Data removal completed within 30 days</li>
      </ul>
    </section>

    <section class="card" aria-labelledby="verify">
      <h2 id="verify">Identity verification</h2>
      <p>To protect your privacy, we may ask you to verify your identity from the email associated with your account, or provide additional proof if needed.</p>
    </section>

    <section class="card" aria-labelledby="contact">
      <h2 id="contact">Contact</h2>
      <p>If you have questions, contact us at <a href="mailto:medexamix@gmail.com">medexamix@gmail.com</a>.</p>
    </section>
  </main>

  <footer>
    © <span id="year"></span> Upex • This page is public and does not require login.
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
