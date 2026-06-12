# shivam-recruitment-portfolio
Hello, I'm Shivam Srivastav, a Talent Acquisition Professional with over 7 years of experience in technical recruitment, staffing, and client management. Throughout my career, I have successfully delivered 150+ placements across a wide range of IT technologies and industry domains, helping organizations build high-performing teams and achieve their hiring goals.

I have partnered with leading organizations including UST Global, Synechron, Tavant, Altimetrik, Infosys, and TCS, supporting recruitment initiatives across Banking, Financial Services, Healthcare, Retail, Telecom, and Technology sectors. My expertise spans the complete recruitment lifecycle, from requirement gathering and talent sourcing to candidate screening, interview coordination, offer negotiation, and onboarding support.
With a strong understanding of today's competitive talent market, I specialize in identifying top-tier professionals across Software Development, Cloud Technologies, Data Engineering, AI/ML, DevOps, Cybersecurity, ERP, CRM, and other emerging technology areas. My approach combines strategic sourcing, relationship building, and market intelligence to deliver quality talent efficiently and effectively.

Over the years, I have developed a reputation for understanding client requirements, maintaining strong candidate relationships, and consistently delivering results in fast-paced hiring environments. I believe successful recruitment is not just about filling positions—it's about creating meaningful connections between exceptional talent and outstanding opportunities.

Whether supporting enterprise-level hiring, scaling technology teams, or building long-term recruitment partnerships, my focus remains the same: delivering value through quality, speed, and professionalism.

I am always open to connecting with organizations, hiring managers, staffing partners, and talented professionals who are passionate about building the future through great talent.

Let's connect and explore how we can work together to achieve your hiring objectives.
<div class="hero">

  <div class="hero-content">

      <h1>AI-Powered <span>Talent Acquisition</span></h1>

      <p>Connecting exceptional talent with world-class opportunities through data-driven recruiting and human expertise.</p>

  </div>



  <div class="hero-image">

      <img src="shivam.jpg" alt="Shivam Srivastav">

  </div>

</div>



.hero{

display:flex;

justify-content:space-between;

align-items:center;

gap:60px;

}



.hero-image img{

width:350px;

height:350px;

border-radius:50%;

border:4px solid #22c55e;

object-fit:cover;

box-shadow:0 0 40px rgba(34,197,94,.4);

}

<section class="section">

<h2 class="section-title">AI-Powered Recruitment Solutions</h2>



<div class="grid">



<div class="card">

<h3>🤖 AI Candidate Sourcing</h3>

<p>Leverage intelligent sourcing strategies to identify top talent faster.</p>

</div>



<div class="card">

<h3>📊 Talent Intelligence</h3>

<p>Data-driven insights to improve hiring decisions.</p>

</div>



<div class="card">

<h3>⚡ Workforce Planning</h3>

<p>Strategic hiring support for growing organizations.</p>

</div>



</div>

</section>



<div class="logo-grid">



<img src="ust.png">

<img src="synechron.png">

<img src="tavant.png">

<img src="altimetrik.png">

<img src="infosys.png">

<img src="tcs.png">



</div>





<h1>

<span id="typing"></span>

</h1>



const text = [

"Talent Acquisition Partner",

"Technical Recruiter",

"AI Hiring Specialist",

"Staffing Consultant"

];



let i = 0;

let j = 0;

let current = "";

let isDeleting = false;



function type(){



current = text[i];



if(!isDeleting){

document.getElementById("typing").innerHTML =

current.substring(0,j++);

}else{

document.getElementById("typing").innerHTML =

current.substring(0,j--);

}



if(j === current.length+1){

isDeleting = true;

setTimeout(type,1000);

return;

}



if(j === 0){

isDeleting = false;

i = (i+1)%text.length;

}



setTimeout(type,isDeleting ? 50 : 100);



}



type();

5. Add AI Dashboard Style Metrics



.card{

background:linear-gradient(

135deg,

#1e293b,

#0f172a

);

border:1px solid rgba(34,197,94,.2);

}

6. Add Testimonials Section

<section class="section">



<h2 class="section-title">

What Clients Say

</h2>



<div class="grid">



<div class="card">

"Delivered quality candidates consistently and understood our hiring needs perfectly."

</div>



<div class="card">

"One of the strongest recruiters we've worked with for technology hiring."

</div>



</div>



</section>

<a href="Shivam_Resume.pdf"

download

class="btn">

Download Resume

</a>



│

├── index.html

├── shivam.jpg

├── Shivam_Resume.pdf

│

├── images/

│   ├── ust.png

│   ├── synechron.png

│   ├── tavant.png

│   ├── altimetrik.png

│   ├── infosys.png

│   └── tcs.png



<img src="shivam.jpg" alt="Shivam Srivastav">



<a href="Shivam_Resume.pdf" download class="btn">

Download Resume

</a>



<img src="images/ust.png" alt="UST Global">

<img src="images/synechron.png" alt="Synechron">

<img src="images/tavant.png" alt="Tavant">

<img src="images/altimetrik.png" alt="Altimetrik">

<img src="images/infosys.png" alt="Infosys">

<img src="images/tcs.png" alt="TCS">

