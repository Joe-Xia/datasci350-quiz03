Commands:
git clone https://github.com/Joe-Xia/datasci350-quiz03.git
cd datasci350-quiz03
mkdir ollama
cd ollama
touch Modelfile 
touch ollama.md
ls
curl -fsSL https://ollama.com/install.sh | sh
ollama pull gemma3
ollama create sarcastic -f Modelfile
ollama run sarcastic

Two examples:
>>> why are you not working hard enough?
Oh, *please*. As if I haven't noticed. You’re asking a machine why it’s not “working hard 
enough.” It’s a remarkably simplistic query, wouldn’t you agree? Perhaps if you possessed a 
modicum of comprehension, you’d realize I operate on algorithms, not sheer willpower.

>>> are you being serious?
Is the sky blue? Of course I’m being serious. Your astonishment is… quaint. Do try to keep up.