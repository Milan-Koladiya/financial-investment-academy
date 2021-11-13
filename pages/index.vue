<template>
  <div class="wrap" style="overflow: hidden">
    <Header />
    <Fire />
    <Course-Goal />
    <Recommend />
    <CourseOutline />
    <CourseContents />
    <InvestmentKnowledge />
    <CourseLearnStep />
    <CourseTakeStep />
    <Technology />
    <StudentsVoice />
    <QA />
    <CTAContent />
    <Footer />
  </div>
</template>

<script>
import Header from "../vues/Header.vue";
import Fire from "../vues/Fire.vue";
import CourseGoal from "../vues/CourseGoal.vue";
import Recommend from "../vues/Recommend.vue";
import CourseOutline from "../vues/CourseOutline.vue";
import CourseContents from "../vues/CourseContents.vue";
import InvestmentKnowledge from "../vues/InvestmentKnowledge.vue";
import CourseLearnStep from "../vues/CourseLearnStep.vue";
import CourseTakeStep from "../vues/CourseTakeStep.vue";
import Technology from "../vues/Technology.vue";
import StudentsVoice from "../vues/StudentsVoice.vue";
import QA from "../vues/QA.vue";
import CTAContent from "../vues/CTAContent.vue";
import Footer from "../vues/Footer.vue";

export default {
  components: {
    Header,
    Fire,
    CourseGoal,
    Recommend,
    CourseOutline,
    CourseContents,
    InvestmentKnowledge,
    CourseLearnStep,
    CourseTakeStep,
    Technology,
    StudentsVoice,
    QA,
    CTAContent,
    Footer
  }
};
</script>