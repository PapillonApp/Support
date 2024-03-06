
<div class="head_container">
  <img
    src="assets/beta.png"
    class="logo_main"
  />
  <div class="head_title">
    <p class="head_title_1">
      Support et documentation utilisateur de Papillon
    </p>
    <p class="head_title_2">
      et des services associés.
    </p>
  </div>
</div>

<div class="cards">
  <a href="navigation" class="card">
    <span class="material-symbols-outlined">
      apps
    </span>
    <h3>Navigation dans l'app</h3>
    <p>
      Naviguez dans l'application de façon fluide et optimisée pour en tirer le meilleur de façon efficace.
    </p>
  </a>
  <a href="fonctionnalites" class="card">
    <span class="material-symbols-outlined">
      menu
    </span>
    <h3>Fonctionnalités disponibles</h3>
    <p>
      Utilisez pleinement votre application de vie scolaire en exploitation au maximum toutes ses fonctionnalités.
    </p>
  </a>
  <a href="parametres" class="card">
    <span class="material-symbols-outlined">
      settings
    </span>
    <h3>Paramètres</h3>
    <p>
      Personnalisez Papillon selon votre personnalité et vos gouts, pour la rendre toujours plus agréable à utiliser.
    </p>
  </a>
</div>

### Mentions légales

<div class="cards">
  <a href="documents/privacy-policy" class="card card_secondary">
    <span class="material-symbols-outlined">
      gavel
    </span>
    <h3>Politique de confidentialité</h3>
    <p>
      Consultez notre politique de confidentialité pour en savoir plus sur la collecte et l'utilisation de vos données.
    </p>
  </a>
  <a href="documents/terms-of-service" class="card card_secondary">
    <span class="material-symbols-outlined">
      assignment
    </span>
    <h3>Conditions d'utilisation</h3>
    <p>
      Consultez nos conditions d'utilisation pour en savoir plus sur les règles d'utilisation de nos services.
    </p>
  </a>
</div>
### Bêta de Papillon
Une bêta de Papillon est disponible pour les utilisateurs qui souhaitent tester les nouvelles fonctionnalités.

[:octicons-arrow-right-24: Rejoindre la bêta de Papillon](https://docs.getpapillon.xyz/contribute/beta/)

<style>
  @import url('https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined');

  .material-symbols-outlined {
    font-family: 'Material Symbols Outlined';
    font-weight: normal;
    font-style: normal;
    font-size: 24px;  /* Preferred icon size */
    display: inline-block;
    line-height: 1;
    text-transform: none;
    letter-spacing: normal;
    word-wrap: normal;
    white-space: nowrap;
    direction: ltr;
  }

  #_1 {
    display: none;
  }
  .head_container {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    gap: 16px;
    margin-bottom: 24px;
  }
  .logo_main {
    width: 60px;
    height: 60px;
  }
  .head_title {
    display: flex;
    flex-direction: column;
    gap: 4px;
  }
  .head_title_1 {
    margin: 0;
    font-size: 1.3em;
    line-height: 1.2;
    font-weight: bold;
  }

  .head_title_2 {
    margin: 0;
    font-size: 1em;
    line-height: 1.2;
    opacity: 0.7;
  }

  .cards {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 16px;
  }

  .card {
    display: flex;
    flex-direction: column;
    gap: 0px;
    padding: 0px;
    border-radius: 8px;

    background-color: var(--md-admonition-bg-color);
    border: 1px solid var(--md-default-fg-color--lighter);

    text-decoration: none;
    color: var(--md-default-fg-color);

    overflow: hidden;

    box-shadow: 0px 1px 3px #00000055;
  }

  .card:hover {
    box-shadow: 0px 2px 6px #00000055;
    transform: translateY(-2px);
  }

  .card * {
    margin: 0;
    padding: 0;
    text-decoration: none;
    color: var(--md-default-fg-color);
  }

  .card .material-symbols-outlined {
    padding: 10px;
    background-color: var(--md-primary-fg-color);

    height: 80px;

    display: flex;
    align-items: center;
    justify-content: center;

    color: #fff;
    font-size: 40px;
  }

  .card_secondary .material-symbols-outlined {
    background-color: var(--md-default-fg-color--lightest);
    color: var(--md-admonition-fg-color);
  }

  .card h3 {
    font-size: 1.1em;
    font-weight: bold;
    text-align: left;
    margin: 12px 12px;
    padding: 0;
    margin-bottom: 8px;
  }

  .card p {
    font-size: 0.85em;
    opacity: 0.8;
    text-align: left;
    margin: 0 12px;
    padding: 0;
    margin-bottom: 12px;
  }
</style>