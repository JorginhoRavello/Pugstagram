<style>
    .Share {
      border: 1px solid rgba(219, 219, 219, 1);
      border-radius: 4px;
      background-color: white;
      margin: 0 0 2em 0;
      width: 300px;
      height: 180px;
      position: absolute;
      top: 300px;
      left: 30%;
      z-index: 9;
      padding: 1em;
    }
    .Share-head {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .Share-head h2 {
      font-size: 16px;
    }
    .Share-head i {
      cursor: pointer;
    }
    .Share-content a {
      display: flex;
      align-items: center;
      text-decoration: none;
      color: black;
      font-size: 14px;
      margin: 2em 0 0 0;
    }
    .Share-content i {
      color: #3b5998;
      margin: 0 0.5em 0 0;
      font-size: 20px;
    }
    .Share-facebook i {
      color: #3b5998;
    }
    .Share-whatsapp i {
      color: #1bd741;
    }
    .Share-twitter {
      color:#1DA1F2
    }
    .share-exit {
      color: red;
      font-size: 20px;
      cursor: pointer;
  }
</style>

<div class="Share">
    <div class="Share-head">
        <h2>Compartir</h2>
        <i class="far fa-times-circle share-exit" on:click />
    </div>
    <div class="Share-content">
        <div class="Share-facebook">
            <a href="https://www.facebook.com/sharer/sharer.php?&u=https://pugstagram.co" target="_blank">
                <i class="fab fa-facebook-square" />
                Compartir en Facebook!
            </a>
        </div>
        <div class="Share-whatsapp">
            <a href="https://api.whatsapp.com/send?&text=mira%20este%20hermoso%20pug%20https://pugstagram.co" target="_blank">
                <i class="fab fa-whatsapp-square" />
                Compartir en Whatsapp!
            </a>
        </div>
        <div class="Share-twitter">
          <a href="https://twitter.com/intent/tweet?text=Aprendiendo%20a%20crear%20un%20enlace%20para%20compartir%20en%20Twitter&url=https://devstagram.netlify.app/"
              target="_blank"
              class="share__link">
              <i class="fab fa-twitter-square share__icon-social" />
              Compartir en Twitter
          </a>
        </div>
    </div>
</div>