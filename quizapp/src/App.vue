<template>
<div class="ctr">
    <div class="questions-ctr">
        <div class="progress">
            <div class="bar"></div>
            <div class="status">Dummy Data 1 out of 3 questions answered</div>
        </div>
        <div class="single-question">
            <div class="question">Dummy Data Sample Question 1</div>
            <div class="answers">
                <div class="answer">Dummy Data Sample  Answer 1</div>
                <div class="answer">Dummy Data Sample  Answer 2</div>
                <div class="answer">Dummy Data Sample  Answer 3</div>
                <div class="answer">Dummy Data Sample  Answer 4</div>
            </div>
        </div>
    </div>
    <div class="result">
        <div class="title">You got dummy sample result 1!</div>
        <div class="desc">
            Enter a short description here about the result.
        </div>
    </div>
    <button type="button" class="reset-btn">Reset</button>
</div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
}
</script>

