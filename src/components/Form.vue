<template>
  <form id="my-form" class="form">
    <div class="flex-div">
      <label class="label-form">Cardholder name</label>
      <input class="input-form" placeholder="e.g. Jane Appleseed" />
    </div>
    <div class="flex-div">
      <label class="label-form">Card number</label>
      <input class="input-form" placeholder="e.g. 1234 5678 9123 0000" />
    </div>
    <div class="flex-div">
      <div class="flex-row">
        <div>
          <label class="label-form">Exp.date (MM/YY)</label>
          <div class="date">
            <input class="input-form MM" placeholder="MM" />
            <input class="input-form YY" placeholder="YY" />
          </div>
        </div>
        <div class="flex-div">
          <label class="label-form">Cvc</label>
          <input class="input-form cvc" />
        </div>
      </div>
    </div>
    <button class="button-form">Confirm</button>
  </form>
</template>
<script setup></script>

<style scoped>
.flex-div {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

.flex-row {
  display: flex;
  flex-direction: row;
}

.label-form {
  text-transform: uppercase;
  font-size: 15px;
  color: black;
}

.input-form {
  border-color: var(--color-border);
  width: 350px;
  font-size: 15px;
  margin-bottom: 20px;
  border-radius: 5px;
  padding: 10px;
}

.input-form:hover {
  border-color: var(--color-border-hover);
}

.input-form::placeholder {
  color: rgb(179, 177, 177);
}

.flex-div .date .input-form {
  width: 75px;
}

.flex-div .date > .input-form {
  margin-right: 20px;
}

.flex-div .input-form.cvc {
  width: 160px;
}

.button-form {
  width: 350px;
  background-color: black;
  color: white;
  border-radius: 10px;
  font-size: 15px;
  padding: 10px 0;
  font-weight: 600;
  cursor: pointer;
}
</style>
