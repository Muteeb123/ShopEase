<h1>ShopEase</h1>

<h2>Overview</h2>
<p>
ShopEase is a basic e-commerce application built with Laravel and Blade templating. It allows users to browse products, add items to their cart, and place orders. The app provides a simple, clean interface for shopping and is designed as a foundation for further e-commerce feature expansion.
</p>

<h2>Features</h2>
<ul>
  <li>Browse products by category</li>
  <li>Add products to cart and manage cart items</li>
  <li>Place orders with basic checkout flow</li>
  <li>User authentication and account management</li>
  <li>Responsive design with Blade templates</li>
  <li>Admin panel for managing products and orders</li>
</ul>

<h2>Tech Stack</h2>
<ul>
  <li>Backend: Laravel</li>
  <li>Frontend: Blade templating engine</li>
  <li>Database: MySQL / PostgreSQL</li>
</ul>

<h2>Setup Instructions</h2>

<h3>1. Clone the Repository</h3>
<pre><code>git clone https://github.com/Muteeb123/ShopEase
cd shopease
</code></pre>

<h3>2. Install PHP Dependencies</h3>
<pre><code>composer install
</code></pre>

<h3>3. Configure Environment</h3>
<ul>
  <li>Copy <code>.env.example</code> to <code>.env</code>:
    <pre><code>cp .env.example .env</code></pre>
  </li>
  <li>Update the <code>.env</code> file with your database credentials and other required configurations.</li>
  <li>Generate an application key:
    <pre><code>php artisan key:generate</code></pre>
  </li>
</ul>

<h3>4. Run Migrations and Seed Database</h3>
<pre><code>php artisan migrate
php artisan db:seed
</code></pre>

<h3>5. Start the Server</h3>
<pre><code>php artisan serve
</code></pre>
<p>By default, the application will be available at <a href="http://127.0.0.1:8000">http://127.0.0.1:8000</a></p>

<h2>Notes</h2>
<ul>
  <li>Ensure PHP and Composer are installed.</li>
  <li>For production deployment, configure caching, queues, and storage properly.</li>
</ul>

<h2>Usage</h2>
<ul>
  <li>Browse products and add them to your cart</li>
  <li>Manage cart items and place orders</li>
  <li>Use the admin panel to manage products and orders</li>
</ul>
