<template>
  <b-card class="card-form">
    <b-form @submit="onSubmit" @reset="onReset" v-if="show" class="form-header">
      <h2>Peça sua conta e cartão de crédito do Nubank</h2>
      <b-form-group
        id="input-group-1"
      >
        <b-form-input
          id="input-1"
          v-model="form.email"
          type="text"
          placeholder="Digite seu CPF"
          required
        ></b-form-input>
      </b-form-group>

      <b-button type="submit" variant="primary" class="btn-header" disabled
        >Continuar <font-awesome-icon icon="arrow-right" class="arrow"
      /></b-button>
    </b-form>
  </b-card>
</template>

<script>
export default {
  name: 'Form',
  data() {
    return {
      form: {
        email: '',
        name: '',
        food: null,
        checked: [],
      },
      foods: [
        { text: 'Select One', value: null },
        'Carrots',
        'Beans',
        'Tomatoes',
        'Corn',
      ],
      show: true,
    };
  },
  methods: {
    onSubmit(event) {
      event.preventDefault();
      // eslint-disable-next-line no-alert
      alert(JSON.stringify(this.form));
    },
    onReset(event) {
      event.preventDefault();
      // Reset our form values
      this.form.email = '';
      this.form.name = '';
      this.form.food = null;
      this.form.checked = [];
      // Trick to reset/clear native browser form validation state
      this.show = false;
      this.$nextTick(() => {
        this.show = true;
      });
    },
  },
};
</script>

<style lang='scss'>
@import "../assets/scss/variables.scss";

.card-form {
  border-radius: 20px !important;
  margin-left: 4rem;
  padding: 0.5rem;
  .form-header {
    h2 {
      font-size: 1.5rem;
      padding-bottom: 3rem;
    }

    input {
      border: none;
      border-bottom: 0.1rem solid rgba(17, 17, 17,  0.25);
      border-radius: 0;
      margin-bottom: 0.8rem;
      font-size: 0.8rem;
      padding: 0;

      &:focus {
        outline: none;
        box-shadow: none;
      }

      &:active {
         outline: none;
        box-shadow: none;
      }
    }
  }
}

.btn-header {
  display: flex !important;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  border-radius: 30px !important;
  border: none !important;
  height: 50px;
  margin-bottom: 1rem;
  cursor: pointer;

  &:disabled {
    background-color: rgba(17, 17, 17, 0.1) !important;
    color: rgba(17, 17, 17, 0.4) !important;
    cursor: not-allowed;
  }
}
</style>
