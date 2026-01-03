# Detyra

Të krijohet një program në gjuhën programuese C++ i cili implementon lojën klasike Tic Tac Toe, duke përdorur funksione të ndara për menaxhimin e tabelës, lojtarëve dhe logjikës së fitores, sipas kërkesave të mëposhtme:

a) Variablat globale
board[3][3]: Matrica që përfaqëson tabelën e lojës me pozicione nga 1 deri në 9.

currentPlayer: Variabla që ruan lojtarin aktiv ('X' ose 'O').

b) Funksioni displayBoard-per te shfaqur tabelën aktuale në ekran në formatin vizual 3x3 duke perdorur edhe  ndarësit | dhe ---+---+--- për ta bërë tabelën më të lexueshm

c) Funksioni switchPlayer per te ndërruar lojtarin aktiv pas çdo lëvizjeje.
(Nëse lojtari është X, kalon në O dhe anasjelltas).

d) Funksioni makeMove

Pranon një numër nga 1 deri në 9.

Llogarit rreshtin dhe kolonën përkatëse.

Vendos simbolin e lojtarit në pozicionin e zgjedhur nëse është i lirë.

Kthen true nëse lëvizja është e vlefshme, përndryshe false.

e) Funksioni checkWin
Kontrollon nëse lojtari aktiv ka fituar lojën.

Verifikon rreshtat, kolonat dhe diagonalet për 3 simbole të njëjta.

f) Funksioni checkDraw

Kontrollon nëse të gjitha pozicionet janë mbushur pa fitues.

Kthen true nëse loja ka përfunduar në barazim.

g) Funksioni main

Shfaq tabelën fillestare.

Lexon zgjedhjen e lojtarit nga tastiera.

Kontrollon vlefshmërinë e lëvizjes.

Pas çdo lëvizjeje kontrollon për fitore ose barazim.

Ndërron lojtarin derisa loja të përfundojë
