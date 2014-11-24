ActiveAuth-WordPress
====================

ActiveAuth two-factor authentication for WordPress

This is wordpress plugin that allows ActiveAuths's two-factor authentication to any wordpress site.

Package:
<ul>
  <li>js - ActiveAuth javascript library</li>
  <li>includes - ActiveAuth php authenticator and settings classes
    <ul>
      <li>ActiveAuthenticator.php - ActiveAuth authenticator class</li>
      <li>ActiveAuthenticatorSettings.php - ActiveAuth authenticator settings class</li>
    </ul>
  </li>
  <li>activeauth.php - Main wordpress plugin php script</li>
</ul>

Usage
====================

<h2>0. Before you start create ActiveAuth account</h2>
<p>
Create an integration account in <a href="http://activeauth.me">ActiveAuth.me</a> to generate your integration and secret keys
</p>

<h2>1. Download plugin</h2>
<p>
Download the plugin. Find your wordpress installation path (/your_path/) and move ActiveAuth plugin (activeauth folder) in /your_path/wp-content/plugins/.
Our plugin is in official WordPress plugins repository. You can download it from there, too or directly from your WP admin panel.
<a href="https://wordpress.org/plugins/active-auth/">Active Auth Plugin</a>
</p>

<h2>2. Login in your worpdress site</h2>
<p>
Go to Plugins->Installed plugins. Find ActiveAuth plugin and activate it. After activation you will see settings and deactivate links. Go to settings. Here you have to enter your keys:
<ul>
  <li>Account - is you email address from integration account in ActiveAuth</li>
  <li>Integration key - your integration key from ActiveAuth</li>
  <li>Secret key - your secret key from ActiveAuth</li>
</ul>
You have more options here.
From "Enable for roles" you can choose to which user roles ActiveAuth should be enabled.
From "Enable2FA" you can Enable/Disable globaly ActiveAuth plugin. IMPORTANT To turn on ActiveAuth you must check this options.
</p>

From Settings->Active Auth you have access to the plugin settings
You are ready for using ActiveAuths's two-factor authentication.
