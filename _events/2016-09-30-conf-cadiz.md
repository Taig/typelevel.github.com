---
layout: event

title: "Typelevel Community Conference Cádiz"
short_title: "Cádiz Community Conference"
date_string: "September 30, 2016"
location: "Palacio de Congresos de Cádiz"
description: "Co-located with Lambda World."

poster_hero: "/img/media/cadiz.jpg"
poster_thumb: "/img/media/cadiz-thumb.jpg"

location_section: true
sponsors_section: true

schedule:

  - time: ""
    title: "Free like the wind and the summer"
    speakers: ["dialelo"]
    summary: "Free Monads and Applicatives are being used by functional programmers for writing applications by separating a DSL for the problem domain from the interpreter for such DSL. This allows us to write our application logic in a purely functional way and do the IO and other effectful computations in the interpreters, using a effect-capturing monad when running our programs. Although they bring great benefits in modularity and composability they have their tradeoffs in terms of boilerplate, performance and simplicity. In this talk I'll explain the strengths and weaknesses of Free Monads/Applicatives for writing both applications and libraries, explore the available libraries in Scala for using this technique and provide examples from our real-world uses of Free. I'll also speak about some of the gotchas that you may find when using Free, provide some tips and suggest future work that can benefit everyone using Free structures."
  - time: ""
    title: "We are reactive! Programming actors as cofree coalgebras"
    speakers: ["jserranohidalgo"]
    summary: "Actor-based technologies such as Akka offer powerful abstractions and tools to cope with the increasing levels of scalability and fault tolerance demanded by applications nowadays. However, functional and non-functional concerns are typically intertwined in Akka-based applications. For instance, the functional requirements of a chat application are what they are, regardless of the deployment strategy we may eventually choose: actor systems, web services, javascript clients, etc. To account for optimum levels of modularity, these requirements should be thus completely decoupled from the Akka implementation. In this talk, we show how to exploit coalgebras, arguably one of the most comprehensive techniques for the description of system dynamics, to shape the implementation of functional requirements of reactive systems. Then, we show how actor systems can be obtained as particular machines derived from coalgebraic specifications, i.e. as cofree coalgebras. We illustrate the advantages of this approach concerning testing, reuse and evolvability of the resulting applications. Last, we show the role that categorical duals of coalgebraic notions (namely, algebras, monads, free algebras, etc.) play in the proposed architecture of reactive systems."  
  - time: ""
    title: "Using Typelevel to make the most of ScalaCheck"
    speakers: ["noelmarkham"]
    summary: "ScalaCheck can be such a powerful tool that sometimes you need to rein in how it operates in order to get the most value, to make your tests as understandable and concise as possible. In the second on my series of ScalaCheck talks, I will discuss the value of adding other Typelevel libraries alongside ScalaCheck, such as Cats, Shapeless, Refined, and a new date/time library, in order to get as much value as possible from this great testing suite without having to make any compromises to quality or coverage."  
  - time: ""
    title: "Bypassing free monads with object algebras	"
    speakers: ["javierfuentes"]
    summary: "Free monads do a great job at representing monadic programs in a purely declarative fashion, without forcing us to commit to particular interpretations. Similarly, they enable a highly modular approach for effect composition through functor coproducts. However, in order to achieve these goodies, programmers will be faced with a major challenge, namely, a deep understanding of GADTs, natural transformations, higher-kinded coproducts, Scala's implicits machinery, etc. We advocate using object algebras to obtain the very same benefits of free monads, at a significant lower cost in terms of entry barriers for novice programmers. We report on our experience at using object algebras in several functional programming courses, and show how both approaches may coexist. Finally, we compare free monads and object algebra encodings from the perspective of initial algebras, and show how to leverage Church encodings to implement non-compositional interpreters of generic monadic programs using pattern matching - without using ADTs at all. In sum, we conclude both approaches to be functionally identical, and point to non-functional differences between them in terms of efficiency, modularity and understandability."  
                
sponsors:
  - name: "47 Degrees"
    logo: "/img/media/sponsors/47_degrees.png"
    link: "http://www.47deg.com/"
    type: "platinum"
    height: 100
  - name: "The Workshop"
    logo: "http://www.lambda.world/img/partners/logo-TheWorkshop.png"
    link: "http://www.theworkshop.com/"
    type: "gold"
    height: 50
  - name: "Ciklum"
    logo: "http://www.lambda.world/img/partners/logo-Ciklum.png"
    link: "https://www.ciklum.com/"
    type: "silver"
    height: 50
  - name: "Workday"
    logo: "http://www.lambda.world/img/partners/logo-workday.svg"
    link: "https://www.workday.com/"
    type: "silver"
    height: 50
    
---

## About the Conference

A day of Typelevel sessions, co-located with [Lambda World](http://www.lambda.world).

On Friday, September 30th,[Lambda World](http://www.lambda.world) will host a Typelevel Unconference during the morning and a few workshops in the afternoon. The day will conclude with a community dinner where attendees can discuss functional concepts while enjoying Flamenco music.

If you're interested in speaking during the unconference, please send us your ideas. This is just to see what people are interested in. There is no review, the actual sessions are decided at the conference! We will publish all the submitted proposals here.

<a class="typeform-share btn large" href="https://jorgegalindocruces.typeform.com/to/dTlYCv" data-mode="2" target="_blank">Send your Proposal</a>
<script>(function(){var qs,js,q,s,d=document,gi=d.getElementById,ce=d.createElement,gt=d.getElementsByTagName,id='typef_orm',b='https://s3-eu-west-1.amazonaws.com/share.typeform.com/';if(!gi.call(d,id)){js=ce.call(d,'script');js.id=id;js.src=b+'share.js';q=gt.call(d,'script')[0];q.parentNode.insertBefore(js,q)}id=id+'_';if(!gi.call(d,id)){qs=ce.call(d,'link');qs.rel='stylesheet';qs.id=id;qs.href=b+'share-button.css';s=gt.call(d,'head')[0];s.appendChild(qs,s)}})()</script>


## Talks proposals

{% assign schedule=page.schedule %}
{% include schedule.html %}

## Venue

This event will take place at the Palacio de Congresos de Cádiz.

{% include venue_map.html %}

## Sponsors

We'd like to thank all our sponsors who help to make the Summit happen:

{% include sponsors.html %}
