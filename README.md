
  <title>Simple Sidebar</title>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f2f2f2;
    }

    /* Sidebar styles */
    .sidebar {
      position: fixed;      /* stays on the side */
      top: 0;
      left: 0;
      width: 220px;
      height: 100vh;        /* full screen height */
      background: white;
      border-right: 1px solid #ddd;
      padding: 20px;
      box-shadow: 2px 0 8px rgba(0,0,0,0.1);
    }

    .sidebar h2 {
      margin-top: 0;
      font-size: 20px;
      color: #333;
    }

    .sidebar a {
      display: block;
      margin: 12px 0;
      text-decoration: none;
      color: #007bff;
      font-weight: bold;
    }

    .sidebar a:hover {
      text-decoration: underline;
    }
  

  <!-- Sidebar -->
  <div class="sidebar">
    <h2>Links</h2>
    <a href="https://google.com" target="_blank">Google</a>
    <a href="https://youtube.com" target="_blank">YouTube</a>
    <a href="https://github.com" target="_blank">GitHub</a>
    <a href="https://example.com" target="_blank">Example</a>
  </div>

