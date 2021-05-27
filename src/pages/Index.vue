<template>
  <Layout>
    <div class="hero container-inner mx-auto flex flex-col sm:flex-row justify-between py-16">
      <div class="text-4xl font-bold w-full text-center">
        <div class="leading-tight">Hola! Welcome to my personal website</div>
      </div>
    </div> <!-- end hero -->

    <div class="container-inner mx-auto">
      <p class="text-lg sm:text-xl">
        I’m an information systems engineer (currently doing a public policy and management master) who loves to work with data.
        I believe in an Internet for good that serves people and communities, empowering them to unleash all their potential.
      </p>

      <div class="flex justify-between items-center py-6">
        <div class="w-full sm:w-1/2 px-8 py-8 sm:py-0">
          <g-image src="../../static/mind_map.svg" alt="browser" />
        </div>
        <div class="w-1/2 px-8 hidden sm:flex justify-end">
          <g-image src="../../static/code_review.svg" alt="mobile" />
        </div>
      </div>
    </div>

    <div class="overflow-x-hidden">
      <div class="projects container-inner mx-auto text-xl border-t border-gray-500 border-b py-16 mb-16 relative">
        <h2 class="font-bold mb-6" id="projects">Here are some projects I've worked on:</h2>

        <div class="absolute right-0" style="top: 50px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <ul class="text-lg sm:text-xl space-y-6">
          <li class="checkmark">
            <div>Virtuagora</div>
            <div class="text-lg text-gray-600">
              Virtuagora is a citizen participation digital platform I co-funded and we deployed more than 10 instances
              for local governments and civil society organizations. Some examples are 
              <a href="https://ingenia.virtuagora.org/">Ingenia</a>, 
              <a href="https://pp.sanlorenzo.gob.ar">San Lorenzo's participatory
              budget</a>, and <a href="https://creatingnetworks.youthsig.org">Creating Networks</a>.
            </div>
          </li>
          <li class="checkmark">
            <div>Lyris IT</div>
            <div class="text-lg text-gray-600">
              I started at <a href="https://lyris.com.ar">Lyris</a> as developer and consultant, building digital
              transformation solutions based on documents management, public key infrastructures and digital
              signatures. Currently I'm its CTO and project manager of
              <a href="https://docs.signar.com.ar/release-notes/10.0.html">Signar</a>, our flagship software.
            </div>
          </li>
          <li class="checkmark">
            <div>Youth IGF Argentina 🇦🇷</div>
            <div class="text-lg text-gray-600">
              Youth Initiatives of the IGF are created with a goal of encouraging and involving young people in a
              substantive discussion on Internet governance. I was a founding member of the Youth Argentina and I'm
              currently an active committee member. I'm also maintaining its 
              <a href="https://youthigfargentina.com.ar">website</a>.
            </div>
          </li>
          <li class="checkmark">
            <div>Embajadores de Internet</div>
            <div class="text-lg text-gray-600">
              Embajadores is a non-profit initiative created by 2016 fellows of ISOC's Youth@IGF program. We aim to
              introduce people in the Internet governance ecosystem generating content in Spanish. You can check our
              <a href="https://www.embajadoresdeinternet.org">website</a>, which I created and I'm in charge of maintaining it.
            </div>
          </li>
          <li class="checkmark">
            <div>LACNIC and FORT project</div>
            <div class="text-lg text-gray-500">
              ~ If you come from RDR this is my highlighted project! ~
            </div>
            <div class="text-lg text-gray-600">
              <a href="https://fortproject.net">FORT</a> is a joint initiative by LACNIC and NIC.MX to contribute to
              RPKI deployment and a more secure and resilient Internet. I joined FORT as a consultant in 2019 and I
              made its <a href="https://www.lacnic.net/innovaportal/file/4298/1/fort-informe-seguridad-ruteo-en.pdf">
              Diagnostic Report</a>. Later, I continued doing research work with LACNIC related to BGP interconnection
              in the LAC region. You can read <a href="https://www.lacnic.net/innovaportal/file/4298/1/lacnic-interconexion-bgp-lac-en.pdf">
              our report</a> or take a look at the <a href="https://github.com/LACNIC/bgplac-toolkit">data toolkit</a>
              I developed to extract data from global BGP collectors and get relevant data about the autonomous systems
              and countries in Latin America. Data is presented on <a href="https://bgplac.labs.lacnic.net">this website</a> too.
            </div>
          </li>
          <li class="checkmark">
            <div>MANRS Fellow</div>
            <div class="text-lg text-gray-600">
              MANRS is a global initiative, supported by the Internet Society, that provides crucial fixes to reduce
              the most common routing threats. The Fellowship allows individuals to bring new perspectives, innovative
              ideas, and recent research experience into the MANRS work to improve routing security. As a fellow I
              posted the following articles “<a href="https://www.manrs.org/2021/03/a-regional-look-into-bgp-incidents-in-2020/">
              A Regional Look into BGP Incidents in 2020</a>” and 
              “<a href="https://www.manrs.org/2020/12/whats-the-as0-roa-policy-and-what-should-i-know-as-a-network-operator/">
              What’s the AS0 ROA policy, and what should I know as a network operator?</a>” on its blog.
            </div>
          </li>
        </ul>
      </div> <!-- end projects -->
    </div>

    <div class="overflow-x-hidden border-gray-200 border-b">
      <div class="get-to-know-me container-inner mx-auto text-xl pb-16 relative">
        <h2 class="font-bold mb-6" id="about">Get to know me:</h2>

        <div class="absolute left-0" style="top: 50px; transform: translateX(-100%)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <div class="flex flex-col sm:flex-row justify-between items-center mb-16">
          <div><g-image src="../../static/avatar.jpg" alt="avatar" class="w-32 h-32 rounded-full mb-8 lg:mb-0" /></div>
          <div class="flex-1 text-lg sm:text-xl ml-6">
            Argentinian Information Systems Engineer. Teacher at Universidad Tecnológica Nacional Santa Fe, co-founder of
            Virtuágora and CTO of Lyris IT. Internet Society’s 25 under 25 awardee. You can watch the following webinar I
            conducted about BGP Interconnection in Latin America.
          </div>
        </div>

        <div class="responsive-container">
          <iframe class="responsive-iframe w-full h-full top-0 left-0 border-0" src="https://www.youtube.com/embed/1Em3-U4O9Nw" style="border:0;" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
      </div> <!-- end get-to-know me -->
    </div>

    <div class="overflow-x-hidden">
      <div class="contact-me bg-background-secondary pt-16">
        <div class="container-inner mx-auto text-xl pb-4 relative">
          <h2 class="font-bold mb-6" id="contact">Contact me:</h2>

          <div class="absolute right-0 top-0" style="transform: translate(100%) rotate(180deg)">
            <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
          </div>

          <p class="mb-12">Please fill the form below to send me an email. I'm open to joining cool projects!</p>

          <div class="text-lg sm:text-lg mb-16">
            <form action="https://formspree.io/f/mrgrpobk" method="POST" class="mb-12">
              <div class="flex flex-wrap mb-6 -mx-4">
                  <div class="w-full md:w-1/2 mb-6 md:mb-0 px-4">
                      <label class="block mb-2 text-copy-primary" for="name">
                          Name
                      </label>

                      <input type="text" name="name" id="name" placeholder="Jon Snow" class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none focus:border-green-700 mb-2 p-4" required>
                  </div>

                  <div class="w-full px-4 md:w-1/2">
                      <label class="block text-copy-primary mb-2" for="email">
                          Email Address
                      </label>

                      <input type="email" name="_replyto" id="email" placeholder="email@example.com"  class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none focus:border-green-700 mb-2 p-4" required>
                  </div>
              </div>

              <div class="w-full mb-12">
                  <label class="block text-copy-primary mb-2" for="message">
                      Message
                  </label>

                  <textarea id="message" rows="5" name="message" class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none appearance-none focus:border-green-700 mb-2 px-4 py-4" placeholder="Enter your message here." required></textarea>
              </div>

              <div class="flex justify-end w-full">
                  <input type="submit" value="Submit" class="block bg-green-700 hover:bg-green-800 text-white text-sm font-semibold tracking-wide uppercase shadow rounded cursor-pointer px-6 py-3">
              </div>
          </form>
          </div>
        </div>
      </div> <!-- end contact-me -->
    </div>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Home'
  }
}
</script>

