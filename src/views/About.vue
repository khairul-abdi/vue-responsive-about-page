<template>
  <div class="about-card">
    <div class="card-title">
      <img height="50px" src="https://i.pinimg.com/originals/d3/69/d9/d369d9056795f553e244da66e8297cca.png" alt="avatar" class="avatar">
      <div class="title-text-content">
        <p>About me</p>
        <h2>Khairul Abdi Dongoran</h2>
      </div>
    </div>
    <div class="card-content">
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim, quo voluptatem ex eaque consectetur consequuntur laudantium quisquam veniam vero nihil, quibusdam sit suscipit quam vitae mollitia aperiam distinctio ipsum dolor harum ipsa eos. Assumenda odio veritatis eos, ipsam quae pariatur. Quisquam expedita magni doloremque obcaecati, nobis incidunt quod, perferendis hic dicta dolor maiores ratione amet nostrum quaerat corrupti? Nesciunt, cum minima provident rem esse necessitatibus nostrum. Doloremque quasi, quidem exercitationem similique rerum, molestiae odit odio, libero optio aperiam saepe quis amet consectetur hic! Illo, vero! Quibusdam facilis nemo cumque cum eaque ullam earum laudantium. Placeat dolor quo ex quis repellendus?</p>
      <table width="100%">
        <tr>
          <th>Requirement</th>
          <th>Solution</th>
        </tr>
        <tr>
          <td>Design</td>
          <td>Photoshop, Figma, Adobe XD</td>
        </tr>
        <tr>
          <td>Front-end</td>
          <td>React.js, Vue.js, Nuxt.js,HTML, CSS, Javascript</td>
        </tr>
        <tr>
          <td>Back-end</td>
          <td>Node.js, Express.js, Java, Python, PHP</td>
        </tr>
        <tr>
          <td>ML</td>
          <td>ML5, Tensorflow, Algorithm Design</td>
        </tr>
        <tr>
          <td>Shop</td>
          <td>Stripe, PayFast, E-commerce, CMS</td>
        </tr>
      </table>

      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat aliquid beatae asperiores nobis, ipsum, distinctio corrupti natus dignissimos, velit suscipit quidem. Quas atque neque optio vel necessitatibus a, deleniti dolore excepturi aut nulla reprehenderit deserunt aliquam enim rem minima ullam ad nisi illum mollitia est maxime totam dicta! Nam, nemo!</p>

      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Illum praesentium magni rem voluptatem maiores consequatur nostrum quae voluptatum explicabo ipsa quasi quia corporis neque ad esse optio error, et sequi dolor ducimus. Sit maiores facere pariatur quis vel saepe expedita harum! Cum reprehenderit blanditiis provident vero nobis laborum expedita aliquid natus praesentium enim atque eligendi tenetur voluptas tempore, odit commodi!</p>
    </div>
  </div>
</template>

<style lang="stylus" scoped>

.about-card
  background #333
  padding 3em
  border-radius 10px
  color white
  .card-title
    display flex
    align-items center
    background #222
    border-radius 10px
    .avatar
      border  1px solid rgba(255, 255, 255, 0.4)
      border-radius 50%
      margin 0 30px
  .title-text-content
    p
      margin-bottom 0
      color rgb(210, 210, 210)
    h2
      margin-top 0

.card-content p
  line-height 1.5
  margin 30px auto

table
  border-spacing 0px
  margin 50px auto
  tr th, tr td
    border 1px solid white
    border-top none
    padding 10px
    text-align center
    &:first-of-type
      border-left none
      border-right none
    &:nth-of-type(2)
      border-left none
      border-right none

</style>
