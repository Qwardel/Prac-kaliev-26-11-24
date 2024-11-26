<script setup>

</script>

<template>
<div class="container">
  <div class="row">
    <div class="col">

      <div class="mb-3">
        <label for="nameLastname" class="form-label">ФИО</label>
        <input type="text" class="form-control" id="namelastname" :class="{'is-invalid': !nameLastname}">
        <div class="invalid-feedback">
    Запоните ФИО
      </div>
      </div>

      <div class="mb-3">
        <label for="date" class="form-label">Дата выдачи зарплаты</label>
        <input type="date" class="form-control" id="date" :class="{'is-invalid': !date}">
        <div class="invalid-feedback">
    Заполните дату выдачи зарплаты
      </div>
      </div>

      <div class="mb-3">
        <label for="days" class="form-label">Количество отработанных дней</label>
        <input type="text" class="form-control" id="days" :class="{'is-invalid': !days}">
        <div class="invalid-feedback">
    Заполните количество отработанных дней
      </div>
      </div>

      <div class="mb-3">
        <label for="salary" class="form-label">Размер заработной платы сотрудника</label>
        <input type="text" class="form-control" id="salary" :class="{'is-invalid': !salary}">
        <div class="invalid-feedback">
    Заполните размер заработной платы сотрудника
      </div>
      </div>

      <button type="button" class="btn btn-light">Добавить</button>

    </div>
  </div>
  </div>
</template>