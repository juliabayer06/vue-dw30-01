<template>
  <div class="container">
    <div class="title">
      <h2>Gerencimento de Jogadores</h2>
    </div>
    <div class="form-input">
      <input type="text" />
      <button>Salvar</button>
    </div>
    <div class="list-times">
      <table>
        <thead>
          <tr>
            <td>ID</td>
            <td>Nomes</td>
            <td>Ações</td>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>1</td>
            <td>Jogador 1</td>
            <td>???</td>
          </tr>
          <tr>
            <td>2</td>
            <td>Jogador 2</td>
            <td>???</td>
          </tr>
          <tr>
            <td>3</td>
            <td>Jogador 3</td>
            <td>???</td>
          </tr>
          <tr>
            <td>1</td>
            <td>Jogador 1</td>
            <td>???</td>
          </tr>
          <tr>
            <td>2</td>
            <td>Jogador 2</td>
            <td>???</td>
          </tr>
          <tr>
            <td>1</td>
            <td>Jogador 1</td>
            <td>???</td>
          </tr>
          <tr>
            <td>2</td>
            <td>Jogador 2</td>
            <td>???</td>
          </tr>
          <tr>
            <td>1</td>
            <td>Jogador 1</td>
            <td>???</td>
          </tr>
          <tr>
            <td>2</td>
            <td>Jogador 2</td>
            <td>???</td>
          </tr>
          <tr>
            <td>1</td>
            <td>Jogador 1</td>
            <td>???</td>
          </tr>
          <tr>
            <td>2</td>
            <td>Jogador 2</td>
            <td>???</td>
          </tr>
          <tr>
            <td>1</td>
            <td>Jogador 1</td>
            <td>???</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>
<style>
.title {
  text-align: center;
  padding: 2rem 0;
}
.form-input {
  display: flex;
  justify-content: center;
}
.form-input input {
  width: 50%;
  border: 1px solid #acc;
  border-radius: 10px;
  padding: 0 0.5rem;
  height: 40px;
}
.form-input button {
  height: 40px;
  margin-left: 1%;
  background-color: rgb(80, 20, 110);
  font-weight: bold;
  border: 1px solid rgba(158, 210, 243, 0.945);
  border-radius: 10px;
  width: 15%;
}
.list-times {
  display: flex;
  justify-content: center;
  padding: 2rem 0;
}
table {
  width: 40%;
  border: 1px solid rgba(158, 210, 243, 0.945);
  border-collapse: collapse;
  text-align: center;
  font-size: 1.1rem;
}
table thead {
  background-color: rgba(158, 210, 243, 0.945);
  color: rgba(158, 210, 243, 0.945);
}
table thead th {
  font-weight: bold;
}
table tbody tr:nth-child(odd) {
  background-color: rgba(52, 6, 59, 0.645);
}
h2 {
  color: rgba(0, 0, 0, 0.649);
}
</style>
