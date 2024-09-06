const stripe = Stripe('pk_test_51Pq2hkAuibAaE7MhpDSLrmBrZ3Lfas9qew1noC72zmofsxfpkQKzcHooVQJG6uVN9pwMJNClq1mh6xrQwPhR2TlE00zIbRZZIM');
 const paymentButton = document.querySelector('#paymentButton');
 
 paymentButton.addEventListener('click', () => {
   stripe.redirectToCheckout({
     sessionId: sessionId
   })
 });