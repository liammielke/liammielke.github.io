# liammielke.github.io
[index.html](https://github.com/user-attachments/files/26763135/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Cutz Barbershop II – Killeen, TX</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Source+Sans+Pro:ital,wght@0,300;0,400;0,600;0,700;0,900;1,400&display=swap" rel="stylesheet" />
  <style>
    * { box-sizing: border-box; }
    body { font-family: 'Source Sans Pro', sans-serif; color: #282828; background: #fff; -webkit-font-smoothing: antialiased; margin: 0; }
    .hero-bg {
      background: #000;
      background-image:
        radial-gradient(ellipse at 20% 50%, rgba(0,221,255,0.05) 0%, transparent 60%),
        radial-gradient(ellipse at 80% 50%, rgba(0,221,255,0.05) 0%, transparent 60%);
    }
    .btn-cyan {
      display: inline-block;
      background: #00DDFF;
      color: #000;
      font-size: 11px;
      font-weight: 700;
      letter-spacing: 0.18em;
      text-transform: uppercase;
      padding: 11px 32px;
      text-decoration: none;
      transition: background 0.2s;
    }
    .btn-cyan:hover { background: #00c4e0; }
    .btn-outline-cyan {
      display: inline-block;
      border: 1px solid #00DDFF;
      color: #00DDFF;
      font-size: 11px;
      font-weight: 700;
      letter-spacing: 0.15em;
      text-transform: uppercase;
      padding: 8px 20px;
      text-decoration: none;
      transition: background 0.2s, color 0.2s;
    }
    .btn-outline-cyan:hover { background: #00DDFF; color: #000; }
    .star { color: #00DDFF; font-size: 16px; }
  </style>
</head>
<body>

  <!-- TOP INFO BAR -->
  <div style="background:#000; color:#aaa; font-size:11px; padding:6px 24px; display:flex; justify-content:space-between; align-items:center;">
    <div style="display:flex; gap:24px;">
      <span>&#9990; (254) 245-8160</span>
      <span>&#128205; 1129 York Ave, Killeen, TX 76541</span>
    </div>
    <div style="display:flex; gap:16px;">
      <a href="#" style="color:#aaa; text-decoration:none;">Facebook</a>
      <a href="#" style="color:#aaa; text-decoration:none;">Instagram</a>
      <a href="#" style="color:#aaa; text-decoration:none;">Google</a>
    </div>
  </div>

  <!-- NAVBAR -->
  <nav style="background:#000; color:#fff; padding:12px 24px; display:flex; align-items:center; justify-content:space-between; position:sticky; top:0; z-index:50;">
    <div style="display:flex; align-items:center; gap:12px;">
      <div style="height:44px; width:44px; border-radius:4px; background:#111; border:1px solid #333; display:flex; align-items:center; justify-content:center; font-size:8px; font-weight:900; color:#00DDFF; letter-spacing:0.05em; line-height:1.2; text-align:center;">CUTZ<br/>II</div>
      <div style="font-size:11px; font-weight:700; letter-spacing:0.08em; text-transform:uppercase; line-height:1.3;">
        Cutz Barbershop<br/>II
      </div>
    </div>
    <ul style="display:flex; gap:28px; list-style:none; margin:0; padding:0; font-size:12px; font-weight:600; letter-spacing:0.12em; text-transform:uppercase;">
      <li><a href="#" style="color:#fff; text-decoration:none;">Home</a></li>
      <li><a href="#services" style="color:#fff; text-decoration:none;">Services</a></li>
      <li><a href="#team" style="color:#fff; text-decoration:none;">Our Team</a></li>
      <li><a href="#gallery" style="color:#fff; text-decoration:none;">Gallery</a></li>
      <li><a href="#contact" style="color:#fff; text-decoration:none;">Contact</a></li>
    </ul>
    <a href="https://booksy.com/en-us/1164428_cutz-ii-barbershop_barber-shop_36238_killeen" target="_blank" rel="noopener" class="btn-outline-cyan">Book Now</a>
  </nav>

  <!-- HERO -->
  <section class="hero-bg" style="position:relative; min-height:440px; display:flex; flex-direction:column; align-items:center; justify-content:center; text-align:center; overflow:hidden; padding:80px 20px;">
    <p style="color:#00DDFF; font-size:11px; font-weight:700; letter-spacing:0.4em; text-transform:uppercase; margin:0 0 18px;">Killeen, Texas</p>
    <h1 style="font-size:clamp(48px,8.5vw,108px); font-weight:900; letter-spacing:0.1em; text-transform:uppercase; color:#fff; margin:0; line-height:1; text-shadow:0 2px 40px rgba(0,0,0,0.8);">
      CUTZ<br/>BARBERSHOP II
    </h1>
    <p style="margin-top:20px; color:#ccc; font-size:14px; letter-spacing:0.1em; max-width:420px; line-height:1.6;">
      Walk-ins welcome · Precision cuts · Military friendly
    </p>
    <div style="margin-top:28px; display:flex; gap:14px; flex-wrap:wrap; justify-content:center;">
      <a href="https://booksy.com/en-us/1164428_cutz-ii-barbershop_barber-shop_36238_killeen" target="_blank" rel="noopener" class="btn-cyan">Book Now</a>
      <a href="#services" class="btn-outline-cyan">Our Services</a>
    </div>
    <!-- rating badge -->
    <div style="margin-top:32px; display:flex; align-items:center; gap:8px; color:#fff; font-size:13px;">
      <span class="star">&#9733;</span><span class="star">&#9733;</span><span class="star">&#9733;</span><span class="star">&#9733;</span><span style="color:#00DDFF; font-size:16px;">&#9733;</span>
      <span style="color:#bbb; font-size:12px;">4.6 stars · 29 reviews</span>
    </div>
    <!-- cyan accent dot -->
    <div style="position:absolute; right:32px; top:32px; width:10px; height:10px; border-radius:50%; background:#00DDFF;"></div>
  </section>

  <!-- SERVICES -->
  <section id="services" style="background:#fff; padding:60px 24px;">
    <div style="max-width:860px; margin:0 auto;">
      <div style="text-align:center; margin-bottom:40px;">
        <h2 style="margin:0; font-size:28px; font-weight:700; color:#00DDFF;">Our Services</h2>
        <p style="margin:10px 0 0; font-size:15px; color:#666;">Quality cuts, clean fades, sharp lines — every time.</p>
      </div>

      <div style="display:grid; grid-template-columns:repeat(3,1fr); gap:20px;">

        <div style="border:1px solid #eee; padding:24px; border-radius:4px; text-align:center;">
          <div style="font-size:28px; margin-bottom:10px;">&#9986;</div>
          <h4 style="font-size:15px; font-weight:700; color:#222; margin:0 0 6px;">Haircut</h4>
          <p style="font-size:13px; color:#888; margin:0 0 10px;">Classic cut, taper, fade, or any style you want.</p>
          <span style="color:#00DDFF; font-size:16px; font-weight:700;">$25+</span>
        </div>

        <div style="border:1px solid #eee; padding:24px; border-radius:4px; text-align:center;">
          <div style="font-size:28px; margin-bottom:10px;">&#128114;</div>
          <h4 style="font-size:15px; font-weight:700; color:#222; margin:0 0 6px;">Skin Fade</h4>
          <p style="font-size:13px; color:#888; margin:0 0 10px;">Smooth gradient fade down to the skin. Clean and sharp.</p>
          <span style="color:#00DDFF; font-size:16px; font-weight:700;">$28+</span>
        </div>

        <div style="border:1px solid #eee; padding:24px; border-radius:4px; text-align:center;">
          <div style="font-size:28px; margin-bottom:10px;">&#128083;</div>
          <h4 style="font-size:15px; font-weight:700; color:#222; margin:0 0 6px;">Beard Trim</h4>
          <p style="font-size:13px; color:#888; margin:0 0 10px;">Shape, line, and define your beard to perfection.</p>
          <span style="color:#00DDFF; font-size:16px; font-weight:700;">$15+</span>
        </div>

        <div style="border:1px solid #eee; padding:24px; border-radius:4px; text-align:center;">
          <div style="font-size:28px; margin-bottom:10px;">&#128247;</div>
          <h4 style="font-size:15px; font-weight:700; color:#222; margin:0 0 6px;">Line Up</h4>
          <p style="font-size:13px; color:#888; margin:0 0 10px;">Crisp edges and clean lines for a polished look.</p>
          <span style="color:#00DDFF; font-size:16px; font-weight:700;">$10+</span>
        </div>

        <div style="border:1px solid #eee; padding:24px; border-radius:4px; text-align:center;">
          <div style="font-size:28px; margin-bottom:10px;">&#9702;</div>
          <h4 style="font-size:15px; font-weight:700; color:#222; margin:0 0 6px;">Hot Lather Shave</h4>
          <p style="font-size:13px; color:#888; margin:0 0 10px;">Traditional straight razor shave with hot lather treatment.</p>
          <span style="color:#00DDFF; font-size:16px; font-weight:700;">$20+</span>
        </div>

        <div style="border:1px solid #eee; padding:24px; border-radius:4px; text-align:center;">
          <div style="font-size:28px; margin-bottom:10px;">&#128102;</div>
          <h4 style="font-size:15px; font-weight:700; color:#222; margin:0 0 6px;">Kids Cut</h4>
          <p style="font-size:13px; color:#888; margin:0 0 10px;">Patient, careful cuts for the little ones. All ages welcome.</p>
          <span style="color:#00DDFF; font-size:16px; font-weight:700;">$20+</span>
        </div>

      </div>
    </div>
  </section>

  <!-- ABOUT / WALK-INS BAND -->
  <section style="background:#1c1c1c; color:#fff; padding:48px 24px; text-align:center;">
    <h3 style="font-size:22px; font-weight:700; letter-spacing:0.05em; margin:0 0 16px;">Walk-Ins Always Welcome</h3>
    <p style="max-width:700px; margin:0 auto; color:#bbb; font-size:15px; line-height:1.75;">
      No appointment needed — just walk in. Located in Killeen, TX, we proudly serve the local community and the military families of Fort Hood. We take our time with every cut and never rush. Come see why customers keep coming back.
    </p>
  </section>

  <!-- OUR TEAM -->
  <section id="team" style="background:#111; color:#fff; padding:60px 24px;">
    <h2 style="text-align:center; font-size:26px; font-weight:700; letter-spacing:0.05em; margin:0 0 40px;">Meet Our Barbers</h2>
    <div style="display:grid; grid-template-columns:repeat(3,1fr); gap:20px; max-width:960px; margin:0 auto;">

      <div style="background:#1d1d1d; border-radius:4px; overflow:hidden; display:flex; flex-direction:column;">
        <img src="https://source.unsplash.com/400x300/?barber,man" style="width:100%; height:200px; object-fit:cover; display:block;" alt="Ronnie – Barber" loading="lazy" />
        <div style="padding:20px; display:flex; flex-direction:column; flex:1;">
          <h4 style="font-size:16px; font-weight:700; color:#00DDFF; margin:0 0 6px;">Ronnie</h4>
          <p style="font-size:13px; color:#999; line-height:1.6; margin:0;">Experienced barber delivering sharp fades and precise cuts for every client.</p>
        </div>
      </div>

      <div style="background:#1d1d1d; border-radius:4px; overflow:hidden; display:flex; flex-direction:column;">
        <img src="https://source.unsplash.com/400x300/?barber,woman,hair" style="width:100%; height:200px; object-fit:cover; display:block;" alt="Ms. Song – Barber" loading="lazy" />
        <div style="padding:20px; display:flex; flex-direction:column; flex:1;">
          <h4 style="font-size:16px; font-weight:700; color:#00DDFF; margin:0 0 6px;">Ms. Song</h4>
          <p style="font-size:13px; color:#999; line-height:1.6; margin:0;">Known for meticulous attention to detail and being amazing with kids. Consistently exceeds expectations.</p>
        </div>
      </div>

      <div style="background:#1d1d1d; border-radius:4px; overflow:hidden; display:flex; flex-direction:column;">
        <img src="https://source.unsplash.com/400x300/?barbershop,interior,chairs" style="width:100%; height:200px; object-fit:cover; display:block;" alt="Barbershop interior" loading="lazy" />
        <div style="padding:20px; display:flex; flex-direction:column; flex:1;">
          <h4 style="font-size:16px; font-weight:700; color:#00DDFF; margin:0 0 6px;">Join Our Team</h4>
          <p style="font-size:13px; color:#999; line-height:1.6; margin:0 0 16px;">Experienced barber? We'd love to have you. Come talk to us.</p>
          <a href="tel:2542458160" class="btn-outline-cyan" style="text-align:center; font-size:11px;">Contact Us</a>
        </div>
      </div>

    </div>
  </section>

  <!-- WHY CHOOSE US -->
  <section style="background:#fff; padding:64px 24px; text-align:center;">
    <p style="color:#00DDFF; font-size:11px; font-weight:700; letter-spacing:0.3em; text-transform:uppercase; margin:0 0 10px;">Killeen's Go-To Shop</p>
    <h2 style="font-size:clamp(24px,3.5vw,38px); font-weight:900; color:#111; margin:0 0 16px; line-height:1.2;">
      Quality Cuts. No Rush.<br/><span style="color:#00DDFF;">Every Single Time.</span>
    </h2>
    <p style="font-size:15px; color:#777; max-width:480px; margin:0 auto 28px; line-height:1.7;">Serving Killeen and the Fort Hood military community. Open 7 days a week, 8AM–7PM. Walk right in.</p>
    <a href="tel:2542458160" class="btn-cyan">Call (254) 245-8160</a>
  </section>

  <!-- REVIEWS SPLIT -->
  <section style="display:grid; grid-template-columns:1fr 1fr; min-height:320px;">
    <div style="background:#1c1c1c; color:#fff; display:flex; flex-direction:column; justify-content:center; padding:56px 48px;">
      <h3 style="font-size:30px; font-weight:900; text-transform:uppercase; letter-spacing:0.06em; margin:0 0 6px; line-height:1.1;">
        What Our<br/><span style="color:#00DDFF;">Customers Say</span>
      </h3>
      <div style="display:flex; margin:12px 0 16px; gap:3px;">
        <span class="star">&#9733;</span><span class="star">&#9733;</span><span class="star">&#9733;</span><span class="star">&#9733;</span><span style="color:#00DDFF; font-size:16px;">&#9733;</span>
        <span style="color:#888; font-size:12px; margin-left:6px; align-self:center;">4.6 / 5</span>
      </div>
      <p style="font-size:13px; color:#bbb; line-height:1.75; margin:0 0 24px; max-width:320px;">
        "I've been to this barber shop several times and I've received excellent haircuts."
      </p>
      <p style="font-size:12px; color:#555;">— James D.</p>
    </div>
    <div style="overflow:hidden; min-height:320px; background:#1e1e1e;">
      <img src="https://source.unsplash.com/800x640/?barber,haircut,cutting" style="width:100%; height:100%; min-height:320px; object-fit:cover; display:block;" alt="Barber at work" loading="lazy" />
    </div>
  </section>

  <!-- OUR GALLERY -->
  <section id="gallery" style="background:#fff; padding:60px 24px;">
    <h2 style="text-align:center; font-size:26px; font-weight:700; letter-spacing:0.04em; margin:0 0 36px;">Our Gallery</h2>
    <div style="display:grid; grid-template-columns:repeat(4,1fr); gap:10px; max-width:960px; margin:0 auto;">
      <div style="aspect-ratio:1; overflow:hidden;"><img src="https://source.unsplash.com/400x400/?fade,haircut" style="width:100%;height:100%;object-fit:cover;display:block;" alt="Fade haircut" loading="lazy" /></div>
      <div style="aspect-ratio:1; overflow:hidden;"><img src="https://source.unsplash.com/400x400/?barber,lineup" style="width:100%;height:100%;object-fit:cover;display:block;" alt="Line up" loading="lazy" /></div>
      <div style="aspect-ratio:1; overflow:hidden;"><img src="https://source.unsplash.com/400x400/?haircut,men" style="width:100%;height:100%;object-fit:cover;display:block;" alt="Men's haircut" loading="lazy" /></div>
      <div style="aspect-ratio:1; overflow:hidden;"><img src="https://source.unsplash.com/400x400/?beard,trim" style="width:100%;height:100%;object-fit:cover;display:block;" alt="Beard trim" loading="lazy" /></div>
      <div style="aspect-ratio:1; overflow:hidden;"><img src="https://source.unsplash.com/400x400/?barber,clippers" style="width:100%;height:100%;object-fit:cover;display:block;" alt="Barber with clippers" loading="lazy" /></div>
      <div style="aspect-ratio:1; overflow:hidden;"><img src="https://source.unsplash.com/400x400/?skin,fade" style="width:100%;height:100%;object-fit:cover;display:block;" alt="Skin fade" loading="lazy" /></div>
      <div style="aspect-ratio:1; overflow:hidden;"><img src="https://source.unsplash.com/400x400/?barbershop,chair" style="width:100%;height:100%;object-fit:cover;display:block;" alt="Barbershop chair" loading="lazy" /></div>
      <div style="aspect-ratio:1; overflow:hidden;"><img src="https://source.unsplash.com/400x400/?barber,scissors" style="width:100%;height:100%;object-fit:cover;display:block;" alt="Barber scissors" loading="lazy" /></div>
    </div>
    <div style="text-align:center; margin-top:28px;">
      <a href="#" class="btn-outline-cyan" style="border-color:#999; color:#666;">View More</a>
    </div>
  </section>

  <!-- REVIEWS GRID -->
  <section style="background:#111; color:#fff; padding:60px 24px; text-align:center;">
    <div style="max-width:960px; margin:0 auto;">
      <h2 style="font-size:22px; font-weight:700; letter-spacing:0.04em; margin:0 0 36px;">More Reviews</h2>
      <div style="display:grid; grid-template-columns:repeat(3,1fr); gap:20px; text-align:left;">

        <div style="background:#1d1d1d; padding:24px; border-radius:4px; border-top:2px solid #00DDFF;">
          <div style="display:flex; gap:2px; margin-bottom:12px;">
            <span class="star" style="font-size:13px;">&#9733;</span><span class="star" style="font-size:13px;">&#9733;</span><span class="star" style="font-size:13px;">&#9733;</span><span class="star" style="font-size:13px;">&#9733;</span><span class="star" style="font-size:13px;">&#9733;</span>
          </div>
          <p style="font-size:13px; color:#bbb; line-height:1.7; margin:0 0 14px;">"Great service!!! Ms. Song was amazing!! She really took her time and was very precise."</p>
          <p style="font-size:11px; color:#555; margin:0;">— Kenny Robinson</p>
        </div>

        <div style="background:#1d1d1d; padding:24px; border-radius:4px; border-top:2px solid #00DDFF;">
          <div style="display:flex; gap:2px; margin-bottom:12px;">
            <span class="star" style="font-size:13px;">&#9733;</span><span class="star" style="font-size:13px;">&#9733;</span><span class="star" style="font-size:13px;">&#9733;</span><span class="star" style="font-size:13px;">&#9733;</span><span class="star" style="font-size:13px;">&#9733;</span>
          </div>
          <p style="font-size:13px; color:#bbb; line-height:1.7; margin:0 0 14px;">"Quick and clean I love it. Best cuts in Killeen — I won't go anywhere else."</p>
          <p style="font-size:11px; color:#555; margin:0;">— Prod. vuneral</p>
        </div>

        <div style="background:#1d1d1d; padding:24px; border-radius:4px; border-top:2px solid #00DDFF;">
          <div style="display:flex; gap:2px; margin-bottom:12px;">
            <span class="star" style="font-size:13px;">&#9733;</span><span class="star" style="font-size:13px;">&#9733;</span><span class="star" style="font-size:13px;">&#9733;</span><span class="star" style="font-size:13px;">&#9733;</span><span class="star" style="font-size:13px;">&#9733;</span>
          </div>
          <p style="font-size:13px; color:#bbb; line-height:1.7; margin:0 0 14px;">"Barber is great! She fixed another barber's mistake and always gets it right. Super kind with kids too."</p>
          <p style="font-size:11px; color:#555; margin:0;">— Anonymous</p>
        </div>

      </div>
    </div>
  </section>

  <!-- HOURS & LOCATION -->
  <section id="contact" style="background:#fff; padding:60px 24px;">
    <h2 style="text-align:center; font-size:26px; font-weight:700; letter-spacing:0.04em; margin:0 0 40px;">Hours &amp; Location</h2>
    <div style="display:grid; grid-template-columns:1fr 1fr; gap:40px; max-width:860px; margin:0 auto;">

      <div>
        <h4 style="font-size:14px; font-weight:700; letter-spacing:0.12em; text-transform:uppercase; color:#222; margin:0 0 18px; border-bottom:2px solid #00DDFF; padding-bottom:8px; display:inline-block;">Hours</h4>
        <table style="width:100%; font-size:14px; color:#555; border-collapse:collapse;">
          <tr style="border-bottom:1px solid #f0f0f0;"><td style="padding:8px 0; color:#333; font-weight:600;">Monday</td><td style="padding:8px 0; text-align:right;">8:00 AM – 7:00 PM</td></tr>
          <tr style="border-bottom:1px solid #f0f0f0;"><td style="padding:8px 0; color:#333; font-weight:600;">Tuesday</td><td style="padding:8px 0; text-align:right;">8:00 AM – 7:00 PM</td></tr>
          <tr style="border-bottom:1px solid #f0f0f0;"><td style="padding:8px 0; color:#333; font-weight:600;">Wednesday</td><td style="padding:8px 0; text-align:right;">8:00 AM – 7:00 PM</td></tr>
          <tr style="border-bottom:1px solid #f0f0f0;"><td style="padding:8px 0; color:#333; font-weight:600;">Thursday</td><td style="padding:8px 0; text-align:right;">8:00 AM – 7:00 PM</td></tr>
          <tr style="border-bottom:1px solid #f0f0f0;"><td style="padding:8px 0; color:#333; font-weight:600;">Friday</td><td style="padding:8px 0; text-align:right;">8:00 AM – 7:00 PM</td></tr>
          <tr style="border-bottom:1px solid #f0f0f0;"><td style="padding:8px 0; color:#333; font-weight:600;">Saturday</td><td style="padding:8px 0; text-align:right;">8:00 AM – 7:00 PM</td></tr>
          <tr><td style="padding:8px 0; color:#333; font-weight:600;">Sunday</td><td style="padding:8px 0; text-align:right;">8:00 AM – 7:00 PM</td></tr>
        </table>
      </div>

      <div>
        <h4 style="font-size:14px; font-weight:700; letter-spacing:0.12em; text-transform:uppercase; color:#222; margin:0 0 18px; border-bottom:2px solid #00DDFF; padding-bottom:8px; display:inline-block;">Find Us</h4>
        <a href="https://www.google.com/maps/search/?api=1&query=Cutz+Barbershop+II+1129+York+Ave+Killeen+TX+76541" target="_blank" rel="noopener" style="display:block; background:#e8eaed; border-radius:4px; height:180px; margin-bottom:16px; text-decoration:none; border:1px solid #ddd; overflow:hidden; position:relative;">
          <img src="https://source.unsplash.com/600x360/?killeen,texas,street" style="width:100%;height:100%;object-fit:cover;display:block;opacity:0.55;" alt="Map" loading="lazy" />
          <div style="position:absolute;inset:0;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:6px;">
            <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 24 24" fill="#00DDFF"><path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5S10.62 6.5 12 6.5s2.5 1.12 2.5 2.5S13.38 11.5 12 11.5z"/></svg>
            <span style="font-size:12px;font-weight:700;color:#111;background:rgba(255,255,255,0.88);padding:4px 10px;border-radius:12px;letter-spacing:0.04em;">Open in Google Maps</span>
          </div>
        </a>
        <p style="font-size:14px; color:#444; margin:0 0 6px; font-weight:600;">1129 York Ave<br/>Killeen, TX 76541</p>
        <p style="font-size:14px; color:#444; margin:6px 0;"><a href="tel:2542458160" style="color:#00DDFF; text-decoration:none; font-weight:700;">(254) 245-8160</a></p>
        <p style="font-size:12px; color:#999; margin:8px 0 0;">Walk-ins welcome · No appointment needed</p>
      </div>

    </div>
  </section>

  <!-- FOOTER -->
  <footer style="background:#000; color:#888; padding:40px 24px 24px;">
    <div style="max-width:960px; margin:0 auto; display:grid; grid-template-columns:repeat(3,1fr); gap:32px; font-size:13px;">
      <div>
        <div style="color:#fff; font-size:11px; font-weight:700; letter-spacing:0.15em; text-transform:uppercase; margin-bottom:14px;">Cutz Barbershop II</div>
        <p style="margin:0; line-height:1.8;">1129 York Ave<br/>Killeen, TX 76541</p>
        <p style="margin:8px 0 0;"><a href="tel:2542458160" style="color:#888; text-decoration:none;">(254) 245-8160</a></p>
        <p style="margin:6px 0 0; color:#555; font-size:12px;">Open 7 days · 8AM–7PM</p>
      </div>
      <div>
        <div style="color:#fff; font-size:11px; font-weight:700; letter-spacing:0.15em; text-transform:uppercase; margin-bottom:14px;">Quick Links</div>
        <ul style="list-style:none; margin:0; padding:0; display:flex; flex-direction:column; gap:8px;">
          <li><a href="#services" style="color:#888; text-decoration:none;">Services</a></li>
          <li><a href="#team" style="color:#888; text-decoration:none;">Our Team</a></li>
          <li><a href="#gallery" style="color:#888; text-decoration:none;">Gallery</a></li>
          <li><a href="#contact" style="color:#888; text-decoration:none;">Hours &amp; Location</a></li>
        </ul>
      </div>
      <div>
        <div style="color:#fff; font-size:11px; font-weight:700; letter-spacing:0.15em; text-transform:uppercase; margin-bottom:14px;">Follow Us</div>
        <div style="display:flex; gap:10px;">
          <a href="#" style="width:36px; height:36px; border-radius:50%; border:1px solid #444; display:flex; align-items:center; justify-content:center; color:#888; font-size:11px; font-weight:700; text-decoration:none;">FB</a>
          <a href="#" style="width:36px; height:36px; border-radius:50%; border:1px solid #444; display:flex; align-items:center; justify-content:center; color:#888; font-size:11px; font-weight:700; text-decoration:none;">IG</a>
          <a href="#" style="width:36px; height:36px; border-radius:50%; border:1px solid #444; display:flex; align-items:center; justify-content:center; color:#888; font-size:11px; font-weight:700; text-decoration:none;">G</a>
        </div>
        <p style="margin:16px 0 0; font-size:12px; color:#555; line-height:1.7;">Walk-ins only.<br/>No appointment needed.</p>
      </div>
    </div>
    <div style="max-width:960px; margin:32px auto 0; padding-top:20px; border-top:1px solid #222; text-align:center; font-size:12px; color:#555;">
      &copy; 2026 Cutz Barbershop II · Killeen, TX · All rights reserved.
    </div>
  </footer>

</body>
</html>
