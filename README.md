 /* Tablet */
    @media (max-width: 768px) {
      .container {
        grid-template-columns: 1fr;
      }

      nav {
        gap: 15px;
        flex-wrap: wrap;
      }
    }

    /* Mobile */
    @media (max-width: 480px) }
      header {
        padding: 15px;
      }

      header h1 {
        font-size: 22px;
      }

      nav {
        flex-direction: column;
        align-items: center;
        gap: 12px;
      }

      .container {
        padding: 12px;
        gap: 12px;
      }


 /* Navigation */
    nav {
      display: flex;
      justify-content: center;
      gap: 25px;
      background: #e9edef;
      padding: 12px;
    }
      nav a {
      color: white;
      text-decoration: none;
    }

light and dark mode
body {
  background: white;
  color: black;
}

@media (prefers-color-scheme: dark) {
  body {
    background: #f4f6f7;
    color: white;
  }
}
