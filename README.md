Roberts Funny Stories

Tell me a story idea and I’ll make it hilarious.


Generate Story
© 2025 RobertsFunnyStories.com | Built by Robertunction generateStory() {
  const input = document.getElementById("userInput").value.trim();
  const storyBox = document.getElementById("storyBox");

  if (!input) {
    storyBox.innerText = "Please enter a story idea first!";
    storyBox.classList.remove("hidden");
    return;
  }

  const randomTwists = [
    "but then a llama in sunglasses hijacked a scooter.",
    "until a talking waffle challenged them to a dance-off.",
    "when suddenly, the moon sneezed and launched them into space.",
    "but everything changed when a raccoon with a lightsaber showed up.",
    "and then the chicken declared war on spaghetti.",
  ];

  const twist = randomTwists[Math.floor(Math.random() * randomTwists.length)];

  const story = `Once upon a time, ${input}. It was going great, ${twist} In the end, everyone laughed and ordered tacos.`;

  storyBox.innerText = story;
  storyBox.classList.remove("hidden");
}
