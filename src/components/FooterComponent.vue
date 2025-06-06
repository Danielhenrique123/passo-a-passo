<template>
<footer>
  <nav>
    <section class="upper-footer">
       <div>
        <p class="footer-title">
          <a href="#">IFbooks</a>
        </p>
        <ul>
          <li><span class="mdi mdi-facebook"></span></li>
          <li><span class="mdi mdi-instagram"></span></li>
          <li><span class="mdi mdi-twitter"></span></li>
        </ul>
       </div>
       <div>
         <p class="contact-tex">Contato</p>
         <p><span class="mdi mdi-phone"></span>+55 47 99999-9999</p>
         <p><span class="mdi mdi-clock"></span>8h às 23h - Seg a Sex</p>
         <p><span class="mdi mdi-email"></span>contato@ifbooks.com.b</p>
          <div class="payment-methods">
           <span class="mdi mdi-visa"></span>
           </div>
       </div>
    </section>
    <section class="lower-footer">
         <p>&copy; Alguns direitos reservados. IFBooks. 2025</p>
    </section>
  </nav>
</footer>

</template>

<style scoped>

footer {
  background-color: #27ae60;
  padding: 2vh 8vw;
  color: #fff;

  .upper-footer {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-bottom: 100px;
    border-bottom: 2px solid #fff;

    & div {
      display: flex;
      flex-direction: column;
      gap: 10px;

      & .footer-title {
        font-size: 1.2rem;
        font-weight: 700;

        & a {
          text-decoration: none;
          color: #fff;
        }
      }

      & .contact-text {
        font-size: 1.1rem;
        font-weight: 700;
      }
    }
  }

  .lower-footer {
    display: flex;
    justify-content: center;
    padding-top: 20px;
    font-size: 0.8rem;
  }

  ul {
    display: flex;
    padding: 0;
    gap: 20px;

    li {
      list-style: none;
      font-size: 1.2rem;
      color: #fff;
    }
  }
}



</style>