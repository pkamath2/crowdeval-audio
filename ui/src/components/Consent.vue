<script setup>
</script>

<template>
  <div id="" class="consent-container">
    <div class="heading-consent"> 2. Research Informed Consent</div>
    <div>
      <table>
        <tr>
          <td style="padding-left: 1%; width: 10%">
            <img src="../assets/No-Logo.png" width="100" />
          </td>
          <td>
            <span style="font-size: larger; font-weight: bold"
              >Welcome to 'Evaluation of interface design and instructions for
              crowdsourced evaluation of audio'</span
            >
          </td>
        </tr>
      </table>
    </div>

    <div>
      <p>
        <span style="font-family: Tahoma, Geneva, sans-serif"
          >Thank you for your interest in this audio evaluation task on
          Mechanical Turk. This page outlines the details with respect to your
          consent to participate in our study.</span
        >
      </p>
      <p>
        <br />
        <span style="font-family: Tahoma, Geneva, sans-serif"
          ><u><strong>Protocol Title:</strong></u
          ><br />
          Evaluation of interface design and instructions for crowdsourced evaluation of audio</span
        >
      </p>

      <p>
        <br />
        <span style="font-family: Tahoma, Geneva, sans-serif"
          ><u><strong>Purpose of this research:</strong></u
          ><br />
          The primary aim of this research is to evaluate the quality of
          interfaces to present sound and articulation of the audio quality
          under test while conducting listening tests online via crowdsourced
          marketplaces such as Amazon's Mechanical Turk. The audio clips under
          test belong to the domain of audio textures (for e.g. a series of
          popping sounds, the ticking sound made by a Geiger counter or the
          sound made by water filling a container) or pitches made by musical
          instruments. The specific goal of this project is to ensure that using
          such interfaces abstract audio qualities such as realism, smoothness,
          naturalness or absence of noise etc., can be evaluated using listening
          tests.</span
        >
      </p>

      <p>
        <br />
        <span style="font-family: Tahoma, Geneva, sans-serif"
          ><u><strong>Contacting Us:</strong></u
          ><br />
          Please use the "Contact this requester" link on the Mechanical Turk's
          HIT details section if you need further details or clarifications on
          the task. The Principal Investigator (the person in charge of this
          research) or his/her representative will answer all of your questions.
          Note: On using this feature, your e-mail address and your name will
          automatically be visible to our research team so that we can reply to
          you.</span
        >
      </p>

      <p>
        <br />
        <span style="font-family: Tahoma, Geneva, sans-serif"
          ><u><strong>Your personal data:</strong></u
          ><br />
          Only the principal investigator and his/her representative has your
          worker ID and this will not be released to any other person. We will
          <u><strong>NOT</strong></u> request Amazon Mechanical Turk for your
          person identifying details. Also, this worker ID data will not be used
          in a publication or presentation. We will use this worker ID only for
          the purposes of correlating consent to HIT responses and distributing
          compensation via Mechanical Turk.</span
        >
      </p>

      <p>
        <span style="font-family: Tahoma, Geneva, sans-serif"
          >All data collected will be kept in accordance to the University's
          Research Data Management Policy. Research data used in any publication
          will be kept for a minimum of 10 years before being discarded.</span
        >
      </p>
    </div>

    <div>
      <br />
      <span style="font-family: Tahoma, Geneva, sans-serif"
        >By accepting the HIT on Amazon's Mechanical Turk, you acknowledge that
        -
      </span>
    </div>

    <ol>
      <li>
        <span style="font-family: Tahoma, Geneva, sans-serif"
          >You have agreed to take part in this&nbsp;research.</span
        >
      </li>
      <li>
        <span style="font-family: Tahoma, Geneva, sans-serif"
          >You have read the instructions on the mechanical turk website and
          details on this form which explains the use of the data you submit for
          this research.</span
        >
      </li>
      <li>
        <span style="font-family: Tahoma, Geneva, sans-serif"
          >You can withdraw from this research at any point of time. If you want
          the data you already submitted to be deleted you will&nbsp;inform the
          Principal Investigator and all your data will be discarded.</span
        >
      </li>
      <li>
        <span style="font-family: Tahoma, Geneva, sans-serif"
          >You will not have any financial benefits that result from the
          commercial development of this research.</span
        >
      </li>
      <li>
        <span style="font-family: Tahoma, Geneva, sans-serif"
          >You agree to be re-contacted for future related studies
          via&nbsp;Amazon's Mechanical Turk website. &nbsp;<span lang="EN-US">
          </span
        ></span>
      </li>
    </ol>
  </div>
</template>
<script>
export default {
  data() {
    return {};
  },
  created() {},
  methods: {
    validateForm(){
      return true;
    }
  }
};
</script>

<style scoped>
.consent-container {
  margin: 2%;
}

.heading-consent {
  width: 100%;
  text-align: center;
  font-weight: bold;
  font-size: 250%;
}
</style>
