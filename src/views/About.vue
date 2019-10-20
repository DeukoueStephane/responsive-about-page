<template>
  <div class="about-card">
    <!-- -->
    <div class="card-title">
      <img height="50px" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQR2d5w2jFAxAwqsATjyCk56Vl7fgaGNduuLTQMUdI1CihYsYdo6A" alt="avatar" class="avatar">
      <div class="title-text-content">
        <p>About me</p>
        <h2>Franck Tchapda</h2>
      </div>
    </div>
    <!-- -->
    <div class="card-content">
      <p>
        Lorem Ipsum is simply dummy text of the printing and typesetting
        industry. Lorem Ipsum has been the industry's standard dummy text
        ever since the 1500s, when an unknown printer took a galley of type
        and scrambled it to make a type specimen book. It has survived not
        only five centuries, but also the leap into electronic typesetting,
        remaining essentially unchanged.
      </p>

      <table width="100%">
        <tr>
          <th>Requirements</th>
          <th>Solution</th>
        </tr>
        <tr>
          <td>Design</td>
          <td>PhotoShop, Figma, Canva, Adobe XD</td>
        </tr>
        <tr>
          <td>Frontend</td>
          <td>Vue.js, React.js, HTML, CSS, JavaScript</td>
        </tr>
        <tr>
          <td>Backend</td>
          <td>Node js, PHP, Java, Python</td>
        </tr>
      </table>

      <p>
        Lorem Ipsum is simply dummy text of the printing and typesetting
        industry. Lorem Ipsum has been the industry's standard dummy text
        ever since the 1500s, when an unknown printer took a galley of type
        and scrambled it to make a type specimen book. It has survived not
        only five centuries, but also the leap into electronic typesetting,
        remaining essentially unchanged.
      </p>
      <p>
        Lorem Ipsum is simply dummy text of the printing and typesetting
        industry. Lorem Ipsum has been the industry's standard dummy text
        ever since the 1500s, when an unknown printer took a galley of type
        and scrambled it to make a type specimen book. It has survived not
        only five centuries, but also the leap into electronic typesetting,
        remaining essentially unchanged.
      </p>
    </div>
  </div>
</template>

<style lang="sass" scoped>
  .about-card
    background: #333
    padding: 3em
    border-radius: 10px
    color: white
    .card-title
      display: flex
      align-items: center
      background: #222
      border-radius: 10px
      .avatar
        border: 1px solid rgba(255, 255, 255, 0.4)
        border-radius: 50%
        margin: 0 30px
    .title-text-content
      p
        margin-bottom: 1px
        color: rgb(210, 210, 210)
      h2
        margin-top: 0

  .card-content p
    line-height: 1.5
    margin: 30px auto

  table
    border-spacing: 0
    margin: 30px auto
    tr th, tr td
      border: 1px solid #42b983
      border-top: none
      padding: 10px
      text-align-last: center

      
</style>
