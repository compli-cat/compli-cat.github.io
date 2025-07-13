<template>
  <div class="card bg-[var(--transp-b)]">
    <h2>Let's Chat!</h2>
    <p>Send an email to me at
    <a href="mailto:j.o.radford@protonmail.com">j.o.radford@protonmail.com</a>
    </p>or fill in the form below:
    <form>
      <label for="name">Name:</label>
      <input class="bg-[var(--offwhite)]" type="text"   name="name"/>
      <br/>
      <label for="email">Email:</label>
      <input class="bg-[var(--offwhite)]" type="email"  name="email"/>
      <br/>
      <label for="message">Your message:</label> <br/>
      <textarea class="bg-[var(--offwhite)]" name="message"/> <br/>
      <button class="p-3 bg-[var(--transp-a)]" type="submit">Submit</button>
    </form>
  </div>
</template>
