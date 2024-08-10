---
title : "ABOUT ME"
image : "images/backgrounds/yokohama.png"
# button

# button:
#  enable : true
#  label : "CV"
#  link : "#"



experience:
  enable : true
  title : "EXPERIENCE"
  experience_list:
    # experience item loop
    - name : "Software Engineer based in RCH, Setagaya City, Tokyo"
      company : "[Rakuten Mobile Inc.](https://www.linkedin.com/company/rakuten-mobile-network-inc/)"
      duration : "07/2023 - 07/2024"
      content: "I was deeply involved in software development projects and I was managing Kubernetes clusters both in staging lab and on GCP to tests our software. As part of a company initiative, I had the opportunity to mentor four new graduates, aiding in their integration into the team."
    # experience item loop
    - name : "Research Fellow"
      company : "Polytechnic of Turin - DAUIN ([Netgroup](http://netgroup.polito.it/))"
      duration : "05/2021 - 07/2023"
      content: "I actively contributed to multiple projects, particularly focusing on Polycube. Additionally, I authored scientific articles, explored emerging technologies, and provided guidance to 3 thesis students as a co-supervisor ([Francesco Monaco](https://webthesis.biblio.polito.it/22792/), [Leonardo Di Giovanna](https://webthesis.biblio.polito.it/22615/), [Francesco Cappa](https://webthesis.biblio.polito.it/23609/)). During the second year I worked in a project between Rakuten Mobile Inc. and Polytechnic of Turin."
    # experience item loop
    - name : "Thesis work (researcher)"
      company : "Polytechnic of Turin"
      duration : "10/2020-04/2021"
      content : "The title of the thesis was [Toward efficient DDoS detection with eBPF](https://webthesis.biblio.polito.it/18145/). During this thesis work I worked with Professor [Fulvio Risso](https://fulvio.frisso.net/) (supervisor) and also with the PhD students [Federico Parola](https://it.linkedin.com/in/federico-parola-5b496b200) and [Simone Magnani](https://s41m0n.github.io/)."
    # experience item loop
    - name : "Open Source Developer"
      company : "Polytechnic of Turin - [CrownLabs](https://crownlabs.polito.it/)"
      duration : "03/2020-07/2020"
      content : "In this project I worked on the backend part, in particular on the monitoring (Kube-Prometheus, Blackbox Exporter) and if necessary I also switched to the frontend (a little bit), working together with my team mates on the CrownLabs website and on the personal page of a student/professor."
      
    # experience item loop
    - name : "Open Source Developer "
      company : "Polytechnic of Turin - [Polycube](https://github.com/polycube-network/polycube)"
      duration : "11/2019-06/2020"
      content : "The work was focused on the introduction of backward compatible white-box monitoring for the cubes of the Polycube framework. I also had the chance to work with a nice team made up of various colleagues, PhD students and professors."
      
    # experience item loop
    - name : "Trainee Student - [Ubiatar](https://www.getapper.com/getapper-academy)"
      company : "EFFE ERRE SRL"
      duration : "04/2017-09/2017"
      content : "The objective of the internship was the development of a connection between the Ubiatar application and a hardware device such as the combat robot, which during the internship, in the test and production phase has been replaced by a Raspberry with a breadboard on which a small one has been made hardware project."

publications:
  enable : true
  title : "PUBLICATIONS"
  publications_list:
    # publication item loop
    - name : "Creating Disaggregated Network Services with eBPF: the Kubernetes Network Provider Use Case"
      authors : "[Federico Parola](https://it.linkedin.com/in/federico-parola-5b496b200), [Leonardo Di Giovanna](https://www.linkedin.com/in/leonardo-di-giovanna-1a5453107/), Giuseppe Ognibene, [Fulvio Risso](https://fulvio.frisso.net/)"
      collection : "2022 IEEE 8th International Conference on Network Softwarization (NetSoft)"
      organization: "IEEE"
      abstract : "eBPF enables the creation of custom and highly efficient network services. The most prominent examples of such services follow a monolithic approach: this makes the code hard to maintain, to extend and difficult to reuse. This paper leverages the Polycube framework to demonstrate that a disaggregated approach is feasible also with eBPF: it considers a complex network scenario, such as a complete Kubernetes network provider, presenting the resulting architecture and a preliminary perf. evaluation"
    - name : "Enabling Scalable SFCs in Kubernetes with eBPF-based Cross-Connections"
      authors : "[Federico Parola](https://it.linkedin.com/in/federico-parola-5b496b200), [Francesco Monaco](https://www.linkedin.com/in/francesco-monaco-85737b247/), Giuseppe Ognibene, [Fulvio Risso](https://fulvio.frisso.net/)"
      collection : "2022 IEEE Conference on Network Function Virtualization and Software Defined Networks (NFV-SDN)"
      organization: "IEEE"
      abstract : "Service Function Chains (SFCs) are ordered sets of Network Functions (NFs) that provide network services. Telco operators require scalable chains to adapt to fluctuating traffic. While Kubernetes enhances scalability and flexibility for general-purpose applications, it lacks features needed for network services. This paper presents a cloud-native architecture integrating SFCs in Kubernetes, enabling horizontal autoscaling. The solution uses flexible cross-connections to adapt network traffic distribution, validated with an open-source implementation using Kubernetes operators and an eBPF load balancer."
    - name : "eBPF: A New Approach to Cloud-Native Observability, Networking and Security for Current (5G) and Future Mobile Networks (6G and Beyond)"
      authors : "[David Soldani](https://www.linkedin.com/in/dr-david-soldani/), [Petrit Nahi](https://www.linkedin.com/in/pnahi), [Hami Bour](https://au.linkedin.com/in/dr-hami-bour), [
Saber Jafarizadeh](https://au.linkedin.com/in/saber-jafarizadeh-b84b3b44), [Mohammed F. Soliman](https://www.linkedin.com/in/mohammed-fatehy-soliman-phd-cka-csm-pdm-32512326/), [Francesco Monaco](https://www.linkedin.com/in/francesco-monaco-85737b247/),  [Leonardo Di Giovanna](https://www.linkedin.com/in/leonardo-di-giovanna-1a5453107/), Giuseppe Ognibene, [Fulvio Risso](https://fulvio.frisso.net/)"
      collection : "IEEE Access ( Volume: 11)"
      organization: "IEEE"
      abstract : "Cloud-native networks leverage Kubernetes (K8s) and eBPF technology to revolutionize networking, security, and observability. This paper introduces eBPF's potential for Telco cloud and explores innovative pricing models tied to eBPF agents and modules. We present our eBPF platform, Sauron, demonstrating its ability to dynamically load custom code for energy estimation, network monitoring, and real-time security. Experimental results showcase eBPF's efficacy in enhancing performance, observability, and security across current and future mobile networks (5G, 6G)."



# custom style
custom_class: "" 
custom_attributes: "" 
custom_css: ""
---

Hi, I'm Giuseppe (for friends, Pino), a Computer Engineer. I am passionate about the world of computer science, technology in general and Open Source. I like to work in team and learn new ways to solve problems that may arise in front of an engineer 🤯. Resistant to stress, especially thanks to the PoliTo.

* MSc in Computer Engineering (Network Computers) at Polytechnic of Turin [104/110], 04/2021
* BSc in Computer Engineering at Polytechnic of Turin [96/110], 07/2018  