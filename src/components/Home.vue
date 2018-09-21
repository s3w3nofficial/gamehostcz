<template>
  <div class="container wrapper">

    <div id="circles">
      <h1>Lorem ipsum dolor</h1>
      <span class="green">some random text</span>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium eligendi sint rerum debitis nulla aspernatur eaque magnam quidem cupiditate pariatur.</p>
      <div class="row">
        <div class="col-4">
          <img class="img-circle" src="https://via.placeholder.com/300x300" alt="">
          <h3>Lorem, ipsum dolor</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus, fuga!</p>
        </div>
        <div class="col-4">
          <img class="img-circle" src="https://via.placeholder.com/300x300" alt="">
          <h3>Lorem, ipsum dolor</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus, fuga!</p>
        </div>
        <div class="col-4">
          <img class="img-circle" src="https://via.placeholder.com/300x300" alt="">
          <h3>Lorem, ipsum dolor</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus, fuga!</p>
        </div>
      </div>
    </div>

    <div id="pricing">
      <h1>Lorem, ipsum dolor</h1>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus, fuga!</p>
      <table>
        <thead>
          <tr>
            <th>ID</th>
            <th>Neco</th>
            <th>Neco</th>
            <th>Neco</th>
            <th>Neco</th>
            <th>Cena</th>
            <th></th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>1</td>
            <td>
              <p>Lorem ipsum dolor sit amet.</p>
              <p>Lorem ipsum dolor sit amet.</p>
            </td>
            <td>
              <p>Lorem, ipsum dolor.</p>
              <p>Lorem ipsum dolor sit amet.</p>
            </td>
            <td>Lorem, ipsum dolor.</td>
            <td>300</td>
            <td>
              <span class="price">500Kc</span>
              mmm
            </td>
            <td><button class="btn btn-green">Objednat</button></td>
          </tr>
          <tr>
            <td>1</td>
            <td>
              <p>Lorem ipsum dolor sit amet.</p>
              <p>Lorem ipsum dolor sit amet.</p>
            </td>
            <td>
              <p>Lorem, ipsum dolor.</p>
              <p>Lorem ipsum dolor sit amet.</p>
            </td>
            <td>Lorem, ipsum dolor.</td>
            <td>300</td>
            <td>
              <span class="price">500Kc</span>
              mmm
            </td>
            <td><button class="btn btn-green">Objednat</button></td>
          </tr>
          <tr>
            <td>1</td>
            <td>
              <p>Lorem ipsum dolor sit amet.</p>
              <p>Lorem ipsum dolor sit amet.</p>
            </td>
            <td>
              <p>Lorem, ipsum dolor.</p>
              <p>Lorem ipsum dolor sit amet.</p>
            </td>
            <td>Lorem, ipsum dolor.</td>
            <td>300</td>
            <td>
              <span class="price">500Kc</span>
              mmm
            </td>
            <td><button class="btn btn-green">Objednat</button></td>
          </tr>
        </tbody>
      </table>
    </div>

    <div id="games">
      <h1>Lorem, ipsum dolor</h1>
      <h3>Lorem, ipsum.</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima, rem.</p>
      <div class="row">
        <div class="col-4">
          <img src="https://via.placeholder.com/300x200" alt="">
          <h3>Lorem, ipsum dolor</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus, fuga!</p>
          <button class="btn btn-green">Lorem</button>
        </div>
        <div class="col-4">
          <img src="https://via.placeholder.com/300x200" alt="">
          <h3>Lorem, ipsum dolor</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus, fuga!</p>
          <button class="btn btn-green">Lorem</button>
        </div>
        <div class="col-4">
          <img src="https://via.placeholder.com/300x200" alt="">
          <h3>Lorem, ipsum dolor</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus, fuga!</p>
          <button class="btn btn-green">Lorem</button>
        </div>
      </div>
    </div>

    <div id="social">
      <div class="row">
        <div class="col-3">
          <img class="img-circle" src="https://via.placeholder.com/300x300" alt="">
        </div>
        <div class="col-6">
          <h1>Lorem, ipsum dolor</h1>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis, quia!</p>
        </div>
        <div class="col-3">
          <button class="btn btn-green">Lorem</button>
          <span class="green">some random text</span>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nisi, corrupti.</p>
        </div>
      </div>
    </div>

    <div id="servers">
      <h1>Lorem, ipsum dolor</h1>
      <span class="green">some random text</span>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nisi, corrupti.</p>
      <div class="row">
        <div class="col-2-4">
          <div class="circle"></div>
          <h3>Lorem, ipsum dolor</h3>
          <p>Lorem, ipsum</p>
          <button class="btn btn-green">Objednat</button>
        </div>
        <div class="col-2-4">
          <div class="circle"></div>
          <h3>Lorem, ipsum dolor</h3>
          <p>Lorem, ipsum</p>
          <button class="btn btn-green">Objednat</button>
        </div>
        <div class="col-2-4">
          <div class="circle"></div>
          <h3>Lorem, ipsum dolor</h3>
          <p>Lorem, ipsum</p>
          <button class="btn btn-green">Objednat</button>
        </div>
        <div class="col-2-4">
          <div class="circle"></div>
          <h3>Lorem, ipsum dolor</h3>
          <p>Lorem, ipsum</p>
          <button class="btn btn-green">Objednat</button>
        </div>
        <div class="col-2-4">
          <div class="circle"></div>
          <h3>Lorem, ipsum dolor</h3>
          <p>Lorem, ipsum</p>
          <button class="btn btn-green">Objednat</button>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<style lang="sass" scoped>
  .wrapper
    text-align: center
    h1
      font-weight: normal
    .green
      color: #0f0
    #circles
      padding: 60px 0
      img
        width: 150px
        height: 150px
      h3
        font-weight: bold
    #pricing
      padding: 60px 0
      text-align: left
      table
        width: 100%
        border-collapse: collapse
        thead
          background: green
          color: #fff
          font-weight: bold
          th
            padding: 15px
    #games
      padding: 60px 0
    #social
      padding: 60px 60px
      border: 1px solid #000
      .row
        justify-content: center
        align-items: center
        img
          width: 250px
          height: 250px
    #servers
      padding: 60px 0
      margin-bottom: 60px
      .circle
        display: block
        margin: 0 auto
        background: #000
        border-radius: 50%
        width: 150px
        height: 150px
        &:hover
          background: green

</style>

