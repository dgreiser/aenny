<template>
    <div class="content">
        <div id="problems" class="section">
            <Section 
            title="Unser Konzept"
            text="Unsere Vision ist es, Nachhaltigkeit für Eltern einfach und erschwinglich zu machen und dabei den Kindern die Möglichkeit zu bieten, sich eigenständig durch alle Entwicklungsstufen ihres Lebens zu entfalten." />
            <Gallery />
        </div>
        <Quote 
        class="quote-section"
        bg="red"
        text="now ännyone can build ännything, ännywhere, ännytime!"/>
        <div id="special" class="section">
            <Section 
            class="special-section"
            title="Innovation"
            text="Kinderprodukte sind meistens sehr spezifisch in ihrer Funktion, auf die Nutzung in einer begrenzten Lebensphase ausgelegt und nach einer Weile durchgespielt. Unser innovatives Kinderspielmöbel definiert das Spielerlebnis neu, indem es multifunktional, langlebig und sicher für Kinder jeden Alters ist. Dank seines mitwachsenden Designs bietet es eine langfristige Begleitung in der Entwicklung der Kinder und sorgt für grenzenlosen Spaß und Kreativität." />
            <div class="rect-left rect3 mint"></div>
            <div class="scribble-left scribble2">
                <img src="/scribble-dot2.svg">
            </div>
            <div class="special-image">
                <img src="/03-special.jpg">
            </div>
        </div>
        <div id="team" class="section">
            <Section 
            class="team-section"
            title="änny Team"
            text="Hi, wir sind Alina und Anna, das Gründungsteam von änny!
Drei Jahre lang hat Alina unser LernSpielMöbel entwickelt, getestet und optimiert. Nun arbeiten wir gemeinsam daran, das Unternehmen hinter dem Konzept aufzubauen und umzusetzten." />
            <Team />
        </div>
        <div id="history" class="section">
            <Section 
            class="timeline-section"
            title="änny Geschichte"
            text="Wir entwickeln änny jetzt schon seit 3 Jahren. Auf unserem Weg haben uns viele verschiedene Menschen unterstützt. Gemeinsam haben wir einiges erreicht. Sieh selbst!" />
            <Timeline/>
        </div>
    </div>
</template>

<script setup>
import { onMounted } from 'vue'

onMounted(() => {
  window.scrollTo(0, 0)
})
</script>