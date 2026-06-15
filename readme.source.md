```aura width=860 height=360
<div style={{ position:'relative', display:'flex', flexDirection:'column', width:'100%', height:'100%', backgroundColor:'#0E0F14', borderRadius:20, overflow:'hidden', fontFamily:'Inter, sans-serif', border:'1px solid #20242E' }}>
  <style>{`
    @keyframes caret { 0%,49%{opacity:1} 50%,100%{opacity:0} }
    @keyframes glowpulse { 0%,100%{opacity:0.55} 50%{opacity:0.85} }
    #emberglow { animation: glowpulse 7s ease-in-out infinite; }
    #hcaret { animation: caret 1.1s step-end infinite; }
  `}</style>
  <svg width="860" height="360" style={{ position:'absolute', top:0, left:0 }}>
    <defs>
      <radialGradient id="ember" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(255,122,69,0.30)"/>
        <stop offset="100%" stopColor="rgba(255,122,69,0)"/>
      </radialGradient>
      <radialGradient id="mint" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(94,234,212,0.13)"/>
        <stop offset="100%" stopColor="rgba(94,234,212,0)"/>
      </radialGradient>
    </defs>
    <ellipse id="emberglow" cx="770" cy="30" rx="300" ry="230" fill="url(#ember)"/>
    <ellipse cx="50" cy="370" rx="240" ry="180" fill="url(#mint)"/>
  </svg>
  <div style={{ position:'relative', display:'flex', flexDirection:'column', padding:'26px 34px', height:'100%' }}>
    <div style={{ display:'flex', flexDirection:'row', alignItems:'center', justifyContent:'space-between' }}>
      <div style={{ display:'flex', flexDirection:'row', alignItems:'center' }}>
        <div style={{ display:'flex', width:26, height:26, borderRadius:7, backgroundColor:'#FF7A45', alignItems:'center', justifyContent:'center', marginRight:11 }}>
          <span style={{ fontSize:14, fontWeight:800, color:'#0E0F14' }}>A</span>
        </div>
        <span style={{ fontSize:13, color:'#ECEEF3', fontFamily:'monospace', letterSpacing:0.5 }}>akash.deep</span>
      </div>
      <div style={{ display:'flex', flexDirection:'row', alignItems:'center', gap:18 }}>
        <span style={{ fontSize:12, color:'#98A2B3', fontFamily:'monospace' }}>work</span>
        <span style={{ fontSize:12, color:'#98A2B3', fontFamily:'monospace' }}>experience</span>
        <span style={{ fontSize:12, color:'#98A2B3', fontFamily:'monospace' }}>achievements</span>
        <span style={{ fontSize:12, color:'#FF7A45', fontFamily:'monospace' }}>contact</span>
      </div>
    </div>
    <div style={{ display:'flex', flexDirection:'column', flex:1, justifyContent:'center' }}>
      <div style={{ display:'flex', flexDirection:'row', alignItems:'center', marginBottom:14 }}>
        <span style={{ fontSize:12, color:'#FF7A45', fontFamily:'monospace', letterSpacing:1 }}>{'// '}</span>
        <span style={{ fontSize:12, color:'#98A2B3', fontFamily:'monospace', letterSpacing:2, textTransform:'uppercase' }}>full-stack · agentic ai · web3</span>
      </div>
      <span style={{ fontSize:66, fontWeight:800, color:'#ECEEF3', letterSpacing:-2, lineHeight:1 }}>Akash Deep</span>
      <div style={{ display:'flex', flexDirection:'row', alignItems:'center', marginTop:18 }}>
        <span style={{ fontSize:18, color:'#98A2B3', lineHeight:1.4 }}>I build autonomous AI agents and ship them to production</span>
        <span id="hcaret" style={{ fontSize:18, color:'#FF7A45', marginLeft:3 }}>_</span>
      </div>
      <div style={{ display:'flex', flexDirection:'row', alignItems:'center', gap:10, marginTop:26 }}>
        <div style={{ display:'flex', flexDirection:'row', alignItems:'center', padding:'7px 14px', borderRadius:100, backgroundColor:'rgba(94,234,212,0.08)', border:'1px solid rgba(94,234,212,0.25)' }}>
          <div style={{ display:'flex', width:7, height:7, borderRadius:7, backgroundColor:'#5EEAD4', marginRight:8 }}></div>
          <span style={{ fontSize:12, color:'#5EEAD4' }}>Open to roles & collaborations</span>
        </div>
        <div style={{ display:'flex', padding:'7px 14px', borderRadius:100, backgroundColor:'rgba(255,122,69,0.08)', border:'1px solid rgba(255,122,69,0.25)' }}>
          <span style={{ fontSize:12, color:'#FF7A45' }}>GSoC '26 @ Drupal</span>
        </div>
      </div>
    </div>
  </div>
</div>
```

```aura width=860 height=150
<div style={{ position:'relative', display:'flex', flexDirection:'row', alignItems:'center', width:'100%', height:'100%', backgroundColor:'#0E0F14', borderRadius:20, overflow:'hidden', fontFamily:'Inter, sans-serif', border:'1px solid #20242E', padding:'0 20px' }}>
  <svg width="860" height="150" style={{ position:'absolute', top:0, left:0 }}>
    <defs>
      <radialGradient id="sglow" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(255,122,69,0.14)"/>
        <stop offset="100%" stopColor="rgba(255,122,69,0)"/>
      </radialGradient>
    </defs>
    <ellipse cx="430" cy="75" rx="420" ry="150" fill="url(#sglow)"/>
  </svg>
  <div style={{ position:'relative', display:'flex', flexDirection:'column', flex:1, alignItems:'center' }}>
    <span style={{ fontSize:42, fontWeight:800, color:'#FF7A45', lineHeight:1 }}>4+</span>
    <span style={{ fontSize:10, color:'#98A2B3', fontFamily:'monospace', letterSpacing:1.5, textTransform:'uppercase', marginTop:8 }}>Hackathon Wins</span>
  </div>
  <div style={{ display:'flex', width:1, height:46, backgroundColor:'#20242E' }}></div>
  <div style={{ position:'relative', display:'flex', flexDirection:'column', flex:1, alignItems:'center' }}>
    <span style={{ fontSize:42, fontWeight:800, color:'#5EEAD4', lineHeight:1 }}>1681</span>
    <span style={{ fontSize:10, color:'#98A2B3', fontFamily:'monospace', letterSpacing:1.5, textTransform:'uppercase', marginTop:8 }}>LeetCode Peak</span>
  </div>
  <div style={{ display:'flex', width:1, height:46, backgroundColor:'#20242E' }}></div>
  <div style={{ position:'relative', display:'flex', flexDirection:'column', flex:1, alignItems:'center' }}>
    <span style={{ fontSize:42, fontWeight:800, color:'#5EEAD4', lineHeight:1 }}>1275</span>
    <span style={{ fontSize:10, color:'#98A2B3', fontFamily:'monospace', letterSpacing:1.5, textTransform:'uppercase', marginTop:8 }}>Codeforces Peak</span>
  </div>
  <div style={{ display:'flex', width:1, height:46, backgroundColor:'#20242E' }}></div>
  <div style={{ position:'relative', display:'flex', flexDirection:'column', flex:1, alignItems:'center' }}>
    <span style={{ fontSize:42, fontWeight:800, color:'#FF7A45', lineHeight:1 }}>1L+</span>
    <span style={{ fontSize:10, color:'#98A2B3', fontFamily:'monospace', letterSpacing:1.5, textTransform:'uppercase', marginTop:8 }}>Prize Money (INR)</span>
  </div>
</div>
```

```aura width=860 height=240
<div style={{ position:'relative', display:'flex', flexDirection:'column', width:'100%', height:'100%', backgroundColor:'#0E0F14', borderRadius:20, overflow:'hidden', fontFamily:'Inter, sans-serif', border:'1px solid #20242E' }}>
  <svg width="860" height="240" style={{ position:'absolute', top:0, left:0 }}>
    <defs>
      <radialGradient id="aglow" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(94,234,212,0.10)"/>
        <stop offset="100%" stopColor="rgba(94,234,212,0)"/>
      </radialGradient>
    </defs>
    <ellipse cx="60" cy="40" rx="260" ry="180" fill="url(#aglow)"/>
  </svg>
  <div style={{ position:'relative', display:'flex', flexDirection:'column', padding:'26px 34px', height:'100%' }}>
    <div style={{ display:'flex', flexDirection:'row', alignItems:'center', marginBottom:18 }}>
      <div style={{ display:'flex', width:8, height:8, borderRadius:2, backgroundColor:'#FF7A45', marginRight:11 }}></div>
      <span style={{ fontSize:12, color:'#ECEEF3', fontFamily:'monospace', letterSpacing:2, textTransform:'uppercase' }}>About</span>
      <span style={{ fontSize:11, color:'#5B6573', fontFamily:'monospace', marginLeft:11 }}>// who i am</span>
      <div style={{ display:'flex', flex:1, height:1, backgroundColor:'#20242E', marginLeft:14 }}></div>
    </div>
    <div style={{ display:'flex', flexDirection:'row', gap:22, flex:1 }}>
      <div style={{ display:'flex', flexDirection:'column', flex:1, justifyContent:'center' }}>
        <span style={{ fontSize:15, color:'#C5CBD6', lineHeight:1.6 }}>Full-stack developer focused on agentic AI — autonomous agents that take real actions across APIs, payments, and product data. I work end-to-end: React / Next.js up front, Node / Express behind, and LLM-driven agents in between.</span>
        <span style={{ fontSize:13, color:'#5B6573', fontFamily:'monospace', marginTop:14 }}>open-source contributor · competitive programmer · hackathon builder</span>
      </div>
      <div style={{ display:'flex', flexDirection:'column', width:236, flexShrink:0, justifyContent:'center', backgroundColor:'#13141B', borderRadius:14, border:'1px solid #20242E', padding:'18px 20px' }}>
        <span style={{ fontSize:10, color:'#5B6573', fontFamily:'monospace', letterSpacing:2, textTransform:'uppercase', marginBottom:12 }}>Currently</span>
        <div style={{ display:'flex', flexDirection:'row', alignItems:'center' }}>
          <div style={{ display:'flex', width:7, height:7, borderRadius:7, backgroundColor:'#FF7A45', marginRight:9 }}></div>
          <span style={{ fontSize:14, fontWeight:700, color:'#ECEEF3' }}>GSoC '26 @ Drupal</span>
        </div>
        <span style={{ fontSize:12, color:'#98A2B3', marginTop:8, lineHeight:1.4 }}>Building an AI-Powered Configuration Navigator</span>
      </div>
    </div>
  </div>
</div>
```

```aura width=860 height=340
<div style={{ position:'relative', display:'flex', flexDirection:'column', width:'100%', height:'100%', backgroundColor:'#0E0F14', borderRadius:20, overflow:'hidden', fontFamily:'Inter, sans-serif', border:'1px solid #20242E' }}>
  <svg width="860" height="340" style={{ position:'absolute', top:0, left:0 }}>
    <defs>
      <radialGradient id="stglow" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(255,122,69,0.12)"/>
        <stop offset="100%" stopColor="rgba(255,122,69,0)"/>
      </radialGradient>
    </defs>
    <ellipse cx="800" cy="320" rx="280" ry="200" fill="url(#stglow)"/>
  </svg>
  <div style={{ position:'relative', display:'flex', flexDirection:'column', padding:'26px 34px', height:'100%' }}>
    <div style={{ display:'flex', flexDirection:'row', alignItems:'center', marginBottom:22 }}>
      <div style={{ display:'flex', width:8, height:8, borderRadius:2, backgroundColor:'#FF7A45', marginRight:11 }}></div>
      <span style={{ fontSize:12, color:'#ECEEF3', fontFamily:'monospace', letterSpacing:2, textTransform:'uppercase' }}>Stack</span>
      <span style={{ fontSize:11, color:'#5B6573', fontFamily:'monospace', marginLeft:11 }}>// what i build with</span>
      <div style={{ display:'flex', flex:1, height:1, backgroundColor:'#20242E', marginLeft:14 }}></div>
    </div>
    {[
      ['languages', ['C++','JavaScript','TypeScript','PHP','SQL']],
      ['frameworks', ['React','Next.js','Node.js','Express','Drupal','AI Agents']],
      ['databases', ['MongoDB','MySQL']],
      ['tools', ['Git','GitHub','Firebase','IPFS','VS Code']],
      ['core', ['DSA','Web Development','Agentic AI Systems']]
    ].map((row, ri) => (
      <div key={ri} style={{ display:'flex', flexDirection:'row', alignItems:'center', marginBottom:13 }}>
        <span style={{ width:96, fontSize:11, color:'#5B6573', fontFamily:'monospace', textTransform:'uppercase', letterSpacing:1 }}>{row[0]}</span>
        <div style={{ display:'flex', flexDirection:'row', flexWrap:'wrap', gap:8, flex:1 }}>
          {row[1].map((t, i) => (
            <div key={i} style={{ display:'flex', padding:'5px 13px', borderRadius:8, backgroundColor:'#16181F', border:'1px solid #262B37' }}>
              <span style={{ fontSize:12, color:'#C5CBD6' }}>{t}</span>
            </div>
          ))}
        </div>
      </div>
    ))}
  </div>
</div>
```

```aura width=860 height=336
<div style={{ position:'relative', display:'flex', flexDirection:'column', width:'100%', height:'100%', backgroundColor:'#0E0F14', borderRadius:20, overflow:'hidden', fontFamily:'Inter, sans-serif', border:'1px solid #20242E' }}>
  <svg width="860" height="336" style={{ position:'absolute', top:0, left:0 }}>
    <defs>
      <radialGradient id="eglow" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(94,234,212,0.10)"/>
        <stop offset="100%" stopColor="rgba(94,234,212,0)"/>
      </radialGradient>
    </defs>
    <ellipse cx="60" cy="320" rx="260" ry="180" fill="url(#eglow)"/>
  </svg>
  <div style={{ position:'relative', display:'flex', flexDirection:'column', padding:'26px 34px', height:'100%' }}>
    <div style={{ display:'flex', flexDirection:'row', alignItems:'center', marginBottom:18 }}>
      <div style={{ display:'flex', width:8, height:8, borderRadius:2, backgroundColor:'#FF7A45', marginRight:11 }}></div>
      <span style={{ fontSize:12, color:'#ECEEF3', fontFamily:'monospace', letterSpacing:2, textTransform:'uppercase' }}>Experience</span>
      <div style={{ display:'flex', flex:1, height:1, backgroundColor:'#20242E', marginLeft:14 }}></div>
    </div>
    <div style={{ display:'flex', flexDirection:'row', backgroundColor:'#13141B', borderRadius:12, border:'1px solid #20242E', overflow:'hidden', marginBottom:14 }}>
      <div style={{ display:'flex', width:3, backgroundColor:'#FF7A45' }}></div>
      <div style={{ display:'flex', flexDirection:'column', padding:'15px 20px', flex:1 }}>
        <div style={{ display:'flex', flexDirection:'row', alignItems:'baseline', justifyContent:'space-between' }}>
          <span style={{ fontSize:15, fontWeight:700, color:'#ECEEF3' }}>Open Source Contributor — <span style={{ color:'#FF7A45' }}>Google Summer of Code · Drupal</span></span>
          <span style={{ fontSize:11, color:'#5B6573', fontFamily:'monospace' }}>2026</span>
        </div>
        <span style={{ fontSize:12.5, color:'#98A2B3', marginTop:9, lineHeight:1.5 }}>Building an AI-Powered Configuration Navigator — LLMs + NLP translate natural-language queries into precise Drupal config workflows, with fuzzy search, intent matching, and extensible modules/APIs.</span>
      </div>
    </div>
    <div style={{ display:'flex', flexDirection:'row', backgroundColor:'#13141B', borderRadius:12, border:'1px solid #20242E', overflow:'hidden' }}>
      <div style={{ display:'flex', width:3, backgroundColor:'#5EEAD4' }}></div>
      <div style={{ display:'flex', flexDirection:'column', padding:'15px 20px', flex:1 }}>
        <div style={{ display:'flex', flexDirection:'row', alignItems:'baseline', justifyContent:'space-between' }}>
          <span style={{ fontSize:15, fontWeight:700, color:'#ECEEF3' }}>Full-Stack Developer Intern — <span style={{ color:'#5EEAD4' }}>0x.Day</span></span>
          <span style={{ fontSize:11, color:'#5B6573', fontFamily:'monospace' }}>Jun – Dec 2025 · Remote</span>
        </div>
        <span style={{ fontSize:12.5, color:'#98A2B3', marginTop:9, lineHeight:1.5 }}>Built responsive React / Next.js interfaces for Web3 applications, shipped reusable components with optimized rendering, integrated REST APIs, and delivered production-ready releases cross-functionally.</span>
      </div>
    </div>
  </div>
</div>
```

```aura width=860 height=300
<div style={{ position:'relative', display:'flex', flexDirection:'column', width:'100%', height:'100%', backgroundColor:'#0E0F14', borderRadius:20, overflow:'hidden', fontFamily:'Inter, sans-serif', border:'1px solid #20242E' }}>
  <svg width="860" height="300" style={{ position:'absolute', top:0, left:0 }}>
    <defs>
      <radialGradient id="pglow" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(255,122,69,0.12)"/>
        <stop offset="100%" stopColor="rgba(255,122,69,0)"/>
      </radialGradient>
    </defs>
    <ellipse cx="430" cy="20" rx="360" ry="160" fill="url(#pglow)"/>
  </svg>
  <div style={{ position:'relative', display:'flex', flexDirection:'column', padding:'26px 34px', height:'100%' }}>
    <div style={{ display:'flex', flexDirection:'row', alignItems:'center', marginBottom:18 }}>
      <div style={{ display:'flex', width:8, height:8, borderRadius:2, backgroundColor:'#FF7A45', marginRight:11 }}></div>
      <span style={{ fontSize:12, color:'#ECEEF3', fontFamily:'monospace', letterSpacing:2, textTransform:'uppercase' }}>Featured Work</span>
      <div style={{ display:'flex', flex:1, height:1, backgroundColor:'#20242E', marginLeft:14 }}></div>
    </div>
    <div style={{ display:'flex', flexDirection:'row', gap:16, flex:1 }}>
      <div style={{ display:'flex', flexDirection:'column', flex:1, backgroundColor:'#13141B', borderRadius:14, border:'1px solid #20242E', padding:'18px 20px' }}>
        <div style={{ display:'flex', flexDirection:'row', alignItems:'center', justifyContent:'space-between' }}>
          <span style={{ fontSize:13, color:'#FF7A45', fontFamily:'monospace' }}>■ aaso</span>
          <span style={{ fontSize:10, color:'#5B6573', fontFamily:'monospace' }}>vs-code ext</span>
        </div>
        <span style={{ fontSize:15, fontWeight:700, color:'#ECEEF3', marginTop:10 }}>Automated Application Security Optimizer</span>
        <span style={{ fontSize:12.5, color:'#98A2B3', marginTop:8, lineHeight:1.5, flex:1 }}>Detects vulnerabilities and suggests AI-powered remediation. Modular scanning pipeline with real-time alerting — cut repetitive debugging by ~30%.</span>
        <div style={{ display:'flex', flexDirection:'row', flexWrap:'wrap', gap:6, marginTop:12 }}>
          {['TypeScript','Node.js','Express','Python'].map((t,i)=>(<div key={i} style={{ display:'flex', padding:'4px 10px', borderRadius:6, backgroundColor:'#16181F', border:'1px solid #262B37' }}><span style={{ fontSize:11, color:'#98A2B3' }}>{t}</span></div>))}
        </div>
      </div>
      <div style={{ display:'flex', flexDirection:'column', flex:1, backgroundColor:'#13141B', borderRadius:14, border:'1px solid #20242E', padding:'18px 20px' }}>
        <div style={{ display:'flex', flexDirection:'row', alignItems:'center', justifyContent:'space-between' }}>
          <span style={{ fontSize:13, color:'#5EEAD4', fontFamily:'monospace' }}>■ karotask-live</span>
          <span style={{ fontSize:10, color:'#5B6573', fontFamily:'monospace' }}>web app</span>
        </div>
        <span style={{ fontSize:15, fontWeight:700, color:'#ECEEF3', marginTop:10 }}>Karotask Live</span>
        <span style={{ fontSize:12.5, color:'#98A2B3', marginTop:8, lineHeight:1.5, flex:1 }}>Full-stack task-management platform with real-time tracking & collaboration, Firebase authentication, and live database synchronization.</span>
        <div style={{ display:'flex', flexDirection:'row', flexWrap:'wrap', gap:6, marginTop:12 }}>
          {['React','Node.js','Express','Firebase'].map((t,i)=>(<div key={i} style={{ display:'flex', padding:'4px 10px', borderRadius:6, backgroundColor:'#16181F', border:'1px solid #262B37' }}><span style={{ fontSize:11, color:'#98A2B3' }}>{t}</span></div>))}
        </div>
      </div>
    </div>
  </div>
</div>
```

```aura width=860 height=200
<div style={{ position:'relative', display:'flex', flexDirection:'column', width:'100%', height:'100%', backgroundColor:'#0E0F14', borderRadius:20, overflow:'hidden', fontFamily:'Inter, sans-serif', border:'1px solid #20242E' }}>
  <div style={{ position:'relative', display:'flex', flexDirection:'column', padding:'26px 34px', height:'100%' }}>
    <div style={{ display:'flex', flexDirection:'row', alignItems:'center', marginBottom:18 }}>
      <div style={{ display:'flex', width:8, height:8, borderRadius:2, backgroundColor:'#FF7A45', marginRight:11 }}></div>
      <span style={{ fontSize:12, color:'#ECEEF3', fontFamily:'monospace', letterSpacing:2, textTransform:'uppercase' }}>Education</span>
      <div style={{ display:'flex', flex:1, height:1, backgroundColor:'#20242E', marginLeft:14 }}></div>
    </div>
    <div style={{ display:'flex', flexDirection:'row', gap:16, flex:1 }}>
      <div style={{ display:'flex', flexDirection:'row', flex:1, backgroundColor:'#13141B', borderRadius:12, border:'1px solid #20242E', overflow:'hidden' }}>
        <div style={{ display:'flex', width:3, backgroundColor:'#FF7A45' }}></div>
        <div style={{ display:'flex', flexDirection:'column', padding:'16px 20px', flex:1, justifyContent:'center' }}>
          <span style={{ fontSize:14.5, fontWeight:700, color:'#ECEEF3' }}>B.Tech · Computer Science & Engineering</span>
          <span style={{ fontSize:12.5, color:'#98A2B3', marginTop:6 }}>SRM Institute of Science and Technology</span>
          <span style={{ fontSize:11, color:'#5B6573', fontFamily:'monospace', marginTop:8 }}>Delhi-NCR · 2023 – 2027</span>
        </div>
      </div>
      <div style={{ display:'flex', flexDirection:'row', flex:1, backgroundColor:'#13141B', borderRadius:12, border:'1px solid #20242E', overflow:'hidden' }}>
        <div style={{ display:'flex', width:3, backgroundColor:'#5EEAD4' }}></div>
        <div style={{ display:'flex', flexDirection:'column', padding:'16px 20px', flex:1, justifyContent:'center' }}>
          <span style={{ fontSize:14.5, fontWeight:700, color:'#ECEEF3' }}>Class XII · CBSE</span>
          <span style={{ fontSize:12.5, color:'#98A2B3', marginTop:6 }}>C.R.P.F Public School, Delhi</span>
          <span style={{ fontSize:11, color:'#5B6573', fontFamily:'monospace', marginTop:8 }}>96.5% in Class X</span>
        </div>
      </div>
    </div>
  </div>
</div>
```

```aura width=860 height=384
<div style={{ position:'relative', display:'flex', flexDirection:'column', width:'100%', height:'100%', backgroundColor:'#0E0F14', borderRadius:20, overflow:'hidden', fontFamily:'Inter, sans-serif', border:'1px solid #20242E' }}>
  <svg width="860" height="384" style={{ position:'absolute', top:0, left:0 }}>
    <defs>
      <radialGradient id="acglow" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(255,122,69,0.10)"/>
        <stop offset="100%" stopColor="rgba(255,122,69,0)"/>
      </radialGradient>
    </defs>
    <ellipse cx="800" cy="30" rx="280" ry="200" fill="url(#acglow)"/>
  </svg>
  <div style={{ position:'relative', display:'flex', flexDirection:'column', padding:'26px 34px', height:'100%' }}>
    <div style={{ display:'flex', flexDirection:'row', alignItems:'center', marginBottom:18 }}>
      <div style={{ display:'flex', width:8, height:8, borderRadius:2, backgroundColor:'#FF7A45', marginRight:11 }}></div>
      <span style={{ fontSize:12, color:'#ECEEF3', fontFamily:'monospace', letterSpacing:2, textTransform:'uppercase' }}>Achievements</span>
      <span style={{ fontSize:11, color:'#5B6573', fontFamily:'monospace', marginLeft:11 }}>// selected highlights</span>
      <div style={{ display:'flex', flex:1, height:1, backgroundColor:'#20242E', marginLeft:14 }}></div>
    </div>
    <div style={{ display:'flex', flexDirection:'row', flexWrap:'wrap', gap:12 }}>
      {[
        ['#FF7A45','Google Summer of Code 2026','Selected by Drupal for a funded open-source project'],
        ['#5EEAD4','Runner-Up · Novartis NEST 2.0 (2026)','Top 10 of 24,000+ teams · INR 1,00,000 + PPI'],
        ['#FF7A45','Winner · Pirates of the Coral-Bean (2026)','Track 1 — autonomous B2B chargeback agent · MacBook Neo'],
        ['#FF7A45','1st · CodeSparks Hackathon (GDG, 2024)','Google Developers Group'],
        ['#5EEAD4','2nd · DSA Challenge 1.0 (HackHound, 2024)','Algorithmic problem solving'],
        ['#5EEAD4','Top 10 Finalist · HackIndia (2024)','24-hour Web3 hackathon'],
        ['#5EEAD4','4th · Err Hunt (CSI, 2024)','Competitive debugging']
      ].map((a, i) => (
        <div key={i} style={{ display:'flex', flexDirection:'row', width:380, backgroundColor:'#13141B', borderRadius:10, border:'1px solid #20242E', overflow:'hidden' }}>
          <div style={{ display:'flex', width:3, backgroundColor:a[0] }}></div>
          <div style={{ display:'flex', flexDirection:'column', padding:'11px 15px', flex:1 }}>
            <span style={{ fontSize:13, fontWeight:700, color:'#ECEEF3' }}>{a[1]}</span>
            <span style={{ fontSize:11, color:'#98A2B3', marginTop:4 }}>{a[2]}</span>
          </div>
        </div>
      ))}
    </div>
  </div>
</div>
```

```aura width=860 height=190
<div style={{ position:'relative', display:'flex', flexDirection:'column', width:'100%', height:'100%', backgroundColor:'#0E0F14', borderRadius:20, overflow:'hidden', fontFamily:'Inter, sans-serif', border:'1px solid #20242E' }}>
  <div style={{ position:'relative', display:'flex', flexDirection:'column', padding:'26px 34px', height:'100%' }}>
    <div style={{ display:'flex', flexDirection:'row', alignItems:'center', marginBottom:18 }}>
      <div style={{ display:'flex', width:8, height:8, borderRadius:2, backgroundColor:'#FF7A45', marginRight:11 }}></div>
      <span style={{ fontSize:12, color:'#ECEEF3', fontFamily:'monospace', letterSpacing:2, textTransform:'uppercase' }}>Leadership</span>
      <div style={{ display:'flex', flex:1, height:1, backgroundColor:'#20242E', marginLeft:14 }}></div>
    </div>
    <div style={{ display:'flex', flexDirection:'row', gap:16, flex:1 }}>
      <div style={{ display:'flex', flexDirection:'column', flex:1, backgroundColor:'#13141B', borderRadius:12, border:'1px solid #20242E', padding:'16px 20px', justifyContent:'center' }}>
        <span style={{ fontSize:14.5, fontWeight:700, color:'#ECEEF3' }}>President — ISTE, SRM</span>
        <span style={{ fontSize:12, color:'#98A2B3', marginTop:7, lineHeight:1.4 }}>Led CodeWizard, ISTE's national hackathon · built the ISTE SRM & ICRTC sites</span>
        <span style={{ fontSize:11, color:'#5B6573', fontFamily:'monospace', marginTop:8 }}>Sep 2024 – Present</span>
      </div>
      <div style={{ display:'flex', flexDirection:'column', flex:1, backgroundColor:'#13141B', borderRadius:12, border:'1px solid #20242E', padding:'16px 20px', justifyContent:'center' }}>
        <span style={{ fontSize:14.5, fontWeight:700, color:'#ECEEF3' }}>Technical Core Member — CSI, SRM</span>
        <span style={{ fontSize:12, color:'#98A2B3', marginTop:7, lineHeight:1.4 }}>Computer Society of India, SRM chapter</span>
        <span style={{ fontSize:11, color:'#5B6573', fontFamily:'monospace', marginTop:8 }}>Sep 2024 – Present</span>
      </div>
    </div>
  </div>
</div>
```

```aura width=860 height=210
<div style={{ position:'relative', display:'flex', flexDirection:'column', alignItems:'center', justifyContent:'center', width:'100%', height:'100%', backgroundColor:'#0E0F14', borderRadius:20, overflow:'hidden', fontFamily:'Inter, sans-serif', border:'1px solid #20242E' }}>
  <style>{`
    @keyframes cglow { 0%,100%{opacity:0.6} 50%{opacity:0.95} }
    #contactglow { animation: cglow 6s ease-in-out infinite; }
  `}</style>
  <svg width="860" height="210" style={{ position:'absolute', top:0, left:0 }}>
    <defs>
      <radialGradient id="cg" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(255,122,69,0.22)"/>
        <stop offset="100%" stopColor="rgba(255,122,69,0)"/>
      </radialGradient>
    </defs>
    <ellipse id="contactglow" cx="430" cy="240" rx="420" ry="200" fill="url(#cg)"/>
  </svg>
  <div style={{ position:'relative', display:'flex', flexDirection:'column', alignItems:'center' }}>
    <span style={{ fontSize:12, color:'#FF7A45', fontFamily:'monospace', letterSpacing:2, textTransform:'uppercase', marginBottom:12 }}>// contact</span>
    <span style={{ fontSize:34, fontWeight:800, color:'#ECEEF3', letterSpacing:-1 }}>Let's build something.</span>
    <span style={{ fontSize:14, color:'#98A2B3', marginTop:12 }}>Open to roles, collaborations, and ambitious side-quests.</span>
    <span style={{ fontSize:13, color:'#5EEAD4', fontFamily:'monospace', marginTop:14 }}>akashdeep.6374@gmail.com</span>
  </div>
</div>
```

```aura width=152 height=54 link="https://github.com/aydee-akash" inline align=center
<div style={{ display:'flex', alignItems:'center', justifyContent:'center', width:'100%', height:'100%', fontFamily:'Inter, sans-serif' }}>
  <div style={{ display:'flex', flexDirection:'row', alignItems:'center', justifyContent:'center', gap:9, width:124, height:46, backgroundColor:'#16181F', border:'1px solid #2A2F3B', borderRadius:12 }}>
    <img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI0VDRUVGMyIgZD0iTTEyIC4yOTdjLTYuNjMgMC0xMiA1LjM3My0xMiAxMiAwIDUuMzAzIDMuNDM4IDkuOCA4LjIwNSAxMS4zODUuNi4xMTMuODItLjI1OC44Mi0uNTc3IDAtLjI4NS0uMDEtMS4wNC0uMDE1LTIuMDQtMy4zMzguNzI0LTQuMDQyLTEuNjEtNC4wNDItMS42MUM0LjQyMiAxOC4wNyAzLjYzMyAxNy43IDMuNjMzIDE3LjdjLTEuMDg3LS43NDQuMDg0LS43MjkuMDg0LS43MjkgMS4yMDUuMDg0IDEuODM4IDEuMjM2IDEuODM4IDEuMjM2IDEuMDcgMS44MzUgMi44MDkgMS4zMDUgMy40OTUuOTk4LjEwOC0uNzc2LjQxNy0xLjMwNS43Ni0xLjYwNS0yLjY2NS0uMzA1LTUuNDY3LTEuMzM0LTUuNDY3LTUuOTMxIDAtMS4zMTEuNDY5LTIuMzgxIDEuMjM2LTMuMjIxLS4xMjQtLjMwMy0uNTM1LTEuNTI0LjExNy0zLjE3NiAwIDAgMS4wMDgtLjMyMiAzLjMwMSAxLjIzQTExLjUwOSAxMS41MDkgMCAwIDEgMTIgNS44MDNjMS4wMi4wMDUgMi4wNDcuMTM4IDMuMDA2LjQwNCAyLjI5MS0xLjU1MiAzLjI5Ny0xLjIzIDMuMjk3LTEuMjMuNjUzIDEuNjUzLjI0MiAyLjg3NC4xMTggMy4xNzYuNzcuODQgMS4yMzUgMS45MTEgMS4yMzUgMy4yMjEgMCA0LjYwOS0yLjgwNyA1LjYyNC01LjQ3OSA1LjkyMS40My4zNzIuODIzIDEuMTAyLjgyMyAyLjIyMiAwIDEuNjA2LS4wMTQgMi44OTgtLjAxNCAzLjI5MyAwIC4zMjIuMjE2LjY5NC44MjUuNTc2QzIwLjU2NSAyMi4wOTIgMjQgMTcuNTkyIDI0IDEyLjI5N2MwLTYuNjI3LTUuMzczLTEyLTEyLTEyIi8+PC9zdmc+" width="18" height="18" style={{ width:18, height:18 }} />
    <span style={{ fontSize:13.5, color:'#ECEEF3', fontWeight:600 }}>GitHub</span>
  </div>
</div>
```

```aura width=164 height=54 link="https://linkedin.com/in/akash-deep-387121317" inline align=center
<div style={{ display:'flex', alignItems:'center', justifyContent:'center', width:'100%', height:'100%', fontFamily:'Inter, sans-serif' }}>
  <div style={{ display:'flex', flexDirection:'row', alignItems:'center', justifyContent:'center', gap:9, width:136, height:46, backgroundColor:'#16181F', border:'1px solid #2A2F3B', borderRadius:12 }}>
    <img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iIzRGOENGRiIgZD0iTTIwLjQ0NyAyMC40NTJoLTMuNTU0di01LjU2OWMwLTEuMzI4LS4wMjctMy4wMzctMS44NTItMy4wMzctMS44NTMgMC0yLjEzNiAxLjQ0NS0yLjEzNiAyLjkzOXY1LjY2N0g5LjM1MVY5aDMuNDE0djEuNTYxaC4wNDZjLjQ3Ny0uOSAxLjYzNy0xLjg1IDMuMzctMS44NSAzLjYwMSAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYTIuMDYyIDIuMDYyIDAgMCAxLTIuMDYzLTIuMDY1IDIuMDY0IDIuMDY0IDAgMSAxIDIuMDYzIDIuMDY1em0xLjc4MiAxMy4wMTlIMy41NTVWOWgzLjU2NHYxMS40NTJ6TTIyLjIyNSAwSDEuNzcxQy43OTIgMCAwIC43NzQgMCAxLjcyOXYyMC41NDJDMCAyMy4yMjcuNzkyIDI0IDEuNzcxIDI0aDIwLjQ1MUMyMy4yIDI0IDI0IDIzLjIyNyAyNCAyMi4yNzFWMS43MjlDMjQgLjc3NCAyMy4yIDAgMjIuMjIyIDBoLjAwM3oiLz48L3N2Zz4=" width="18" height="18" style={{ width:18, height:18 }} />
    <span style={{ fontSize:13.5, color:'#ECEEF3', fontWeight:600 }}>LinkedIn</span>
  </div>
</div>
```

```aura width=142 height=54 link="mailto:akashdeep.6374@gmail.com" inline align=center
<div style={{ display:'flex', alignItems:'center', justifyContent:'center', width:'100%', height:'100%', fontFamily:'Inter, sans-serif' }}>
  <div style={{ display:'flex', flexDirection:'row', alignItems:'center', justifyContent:'center', gap:9, width:114, height:46, backgroundColor:'#16181F', border:'1px solid #2A2F3B', borderRadius:12 }}>
    <img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI0ZGN0E0NSIgZD0iTTIwIDRINGMtMS4xIDAtMS45OS45LTEuOTkgMkwyIDE4YzAgMS4xLjkgMiAyIDJoMTZjMS4xIDAgMi0uOSAyLTJWNmMwLTEuMS0uOS0yLTItMnptMCA0bC04IDUtOC01VjZsOCA1IDgtNXYyeiIvPjwvc3ZnPg==" width="18" height="18" style={{ width:18, height:18 }} />
    <span style={{ fontSize:13.5, color:'#ECEEF3', fontWeight:600 }}>Email</span>
  </div>
</div>
```
