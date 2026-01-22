const ui = document.getElementById("ui");
const text = "I love you ❤️";
const count = 120;

for (let i = 0; i < count; i++) {
  const span = document.createElement("span");
  span.className = "love_word";
  span.innerText = text;

  const t = i / count * Math.PI * 2;

  const x = 16 * Math.pow(Math.sin(t), 3);
  const y =
    13 * Math.cos(t) -
    5 * Math.cos(2 * t) -
    2 * Math.cos(3 * t) -
    Math.cos(4 * t);

  span.style.left = x * 15 + "px";
  span.style.top = -y * 15 + "px";
  span.style.transform = `rotate(${t}rad)`;

  ui.appendChild(span);
}
