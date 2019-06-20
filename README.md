# Tetris-free
My first git

	<html>
	<head>
		<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
		<meta name="generator" content="SAEditU Unicode editor, XHTML plug-in, (c) 2004, 2007 by S A Kryukov, http://www.SAKryukov.org" />
		<title>Tetris on Canvas</title>
		<style type="text/css">
			/* http://www.w3schools.com/cssref/css_colornames.asp */ /* for color shading/mixing */
			body, html { font-family: Verdana, sans-serif; background-color: Brown; }
			.noselect { -webkit-touch-callout: none; -webkit-user-select: none; -khtml-user-select: none; -moz-user-select: none; -ms-user-select: none; user-select: none; }
			#main { display:table; background-color: snow; border: solid black 0px; border-radius: 8px; box-shadow: 10px 10px 10px #320D0D; }
			#left, #right { display: table-cell; white-space: nowrap; vertical-align: middle; text-align: center; }
			canvas { background-color: LemonChiffon; width:100%; }
			#upcoming { background-color: /* #DBAAAA; */ Lavender; outline: solid black thin; }
			#score, #rows { font-style: normal; font-weight: bold; }
			#score { color: red; }
			#rows { color: darkGreen; }
			#prompt { margin-top: 3em; margin-bottom: 4em; }
			svg {
				position: absolute;
				left: 0.4em; top: 0.4em;
				cursor: help;
			}
			#help { position: absolute; left: 4em; right: 4em; top: 2em; padding: 2em; padding-top: 0.1em; background-color: white; border: solid black 2px; cursor: help; }
			h1 { text-align: center; font-size:120%; }
      #bad-browser { color: red; text-align: left; }
		</style> 
	</head>
<body>

 <svg
   xmlns:dc="http://purl.org/dc/elements/1.1/"
   xmlns:cc="http://creativecommons.org/ns#"
   xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
   xmlns:svg="http://www.w3.org/2000/svg"
   xmlns="http://www.w3.org/2000/svg"
   xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd"
   xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape"
   width="8mm"
   height="8mm"
   viewBox="0 0 84 84"
   version="1.1"
   inkscape:version="0.92.1 r15371"
   sodipodi:docname="help.svg">
  <g
     inkscape:label="Pad"
     inkscape:groupmode="layer"
     id="id.pad"
     style="display:none"
     transform="translate(219.58333,-242.08333)">
    <rect
       style="opacity:1;vector-effect:none;fill:#ff0000;fill-opacity:1;stroke:none;stroke-width:4.4000001;stroke-linecap:round;stroke-linejoin:miter;stroke-miterlimit:4;stroke-dasharray:none;stroke-dashoffset:0;stroke-opacity:1;paint-order:fill markers stroke"
       id="rect4521-7"
       width="84"
       height="84"
       x="-219.58333"
       y="242.08333" />
  </g>
  <g
     inkscape:groupmode="layer"
     id="id.exit"
     inkscape:label="Exit"
     style="display:none"
     transform="translate(219.58333,-242.08333)">
    <g
       id="g4662">
      <g
         aria-label="X"
         transform="scale(1.0507459,0.95170488)"
         style="font-style:normal;font-weight:normal;font-size:90.42823029px;line-height:0%;font-family:Sans;letter-spacing:0px;word-spacing:0px;fill:#d40000;fill-opacity:1;stroke:none;stroke-width:0.26458332px;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1"
         id="text4493-4">
        <g
           id="g4509">
          <rect
             style="display:inline;opacity:1;vector-effect:none;fill:#ffff00;fill-opacity:1;stroke:#000000;stroke-width:4.4000001;stroke-linecap:round;stroke-linejoin:miter;stroke-miterlimit:4;stroke-dasharray:none;stroke-dashoffset:0;stroke-opacity:1;paint-order:fill markers stroke"
             id="rect4521"
             width="74.708336"
             height="74.708336"
             x="-214.9375"
             y="246.72916"
             transform="scale(0.95170489,1.0507459)" />
          <path
             inkscape:connector-curvature="0"
             id="path4503"
             style="font-size:90.42823029px;fill:#d40000;stroke-width:0.26458332px"
             d="m -141.01302,265.62643 -22.69537,32.49764 22.65122,33.24827 h -10.11136 l -17.92669,-27.06665 -18.36824,27.06665 h -9.53735 l 22.91614,-32.85088 -22.38629,-32.89503 h 10.06721 l 17.70592,26.71342 18.1033,-26.71342 z" />
        </g>
      </g>
    </g>
  </g>
  <g
     inkscape:groupmode="layer"
     id="id.help"
     inkscape:label="Help"
     style="display:inline"
     transform="translate(219.58333,-242.08333)">
    <circle
       style="opacity:1;vector-effect:none;fill:#ffff00;fill-opacity:1;stroke:#000000;stroke-width:4.4000001;stroke-linecap:round;stroke-linejoin:miter;stroke-miterlimit:4;stroke-dasharray:none;stroke-dashoffset:0;stroke-opacity:1;paint-order:fill markers stroke"
       id="path4529"
       cx="-177.58333"
       cy="284.08334"
       r="37.354168" />
    <g
       aria-label="F1"
       style="font-style:normal;font-weight:normal;font-size:50.79999924px;line-height:0%;font-family:Sans;letter-spacing:0px;word-spacing:0px;fill:#000000;fill-opacity:1;stroke:none;stroke-width:0.26458332px;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1"
       id="text4493">
      <path
         d="m -179.00835,270.0439 h -18.67793 v 10.41797 h 16.04863 v 4.36563 h -16.04863 v 17.78496 h -4.91133 v -36.93418 h 23.58926 z"
         style="font-size:50.79999924px;stroke-width:0.26458332px"
         id="path4498"
         inkscape:connector-curvature="0" />
      <path
         d="m -151.49995,302.61246 h -19.99258 v -3.77032 h 7.68945 v -24.75507 h -7.68945 v -3.37344 q 1.56269,0 3.34863,-0.24805 1.78594,-0.27285 2.70371,-0.76894 1.14102,-0.62012 1.78594,-1.5627 0.66973,-0.96738 0.76894,-2.57969 h 3.84473 v 33.28789 h 7.54063 z"
         style="font-size:50.79999924px;stroke-width:0.26458332px"
         id="path4500"
         inkscape:connector-curvature="0" />
    </g>
  </g>
</svg>

 <div id="help">
<h1>Tetris on Canvas v.<span id="version"><span></h1>
<h1 id="bad-browser"><big>If you can see this line, your browser does not support requred essential features</big></h1>
<p><big>&larr;</big>, <big>&rarr;</big>, <big>&darr;</big>: move</p>
<p><big>&uarr;</big>: rotate <big>&orarr;</big></p>
<p>Space: drop down</p>
<p>Enter: start/pause/continue game</p>
<p>Escape: cancel game</p>
<p>F1: show/hide help</p><hr/>
<p>Please see: <a href="LICENSE.txt">License</a>, <a href="http://en.wikipedia.org/wiki/Tetris">about original game</a>, <a href="contributors.html">contributors</a>, <a href="http://www.codeproject.com/Articles/876475/Tetris-On-Canvas">original publication</a>.</p>
<br/><p>Press F1 or click on this text or &cross; to close help window&hellip;</p>
</div>

 <div id="main">
	<div id="left">
		<p id="prompt">&nbsp;&nbsp;Press Enter&nbsp;&nbsp;<br/>to <span id="statusVerb"/></p>
		<div><canvas id="upcoming"/></div>
		<br/><br/><p>Score: <em id="score"></em></p>
		<p>Rows: <em id="rows"></em></p>
		<br/><p id="paused">Paused</p>
	</div>
	<div id="right"><canvas id="board"/></div>
</div>

 <script>
    "use strict";

 const version = "3.0";

 const gameSizeInBlocks = { x:10, y:20 };

 const key = {
	start: 13,	// Enter (start/pause/continue)
	cancel: 27,	// Esc
	left: 37,
	rotate: 38,	// Up
	right: 39,
	down: 40,
	dropDown: 32,	// Space
	help: 112	// F1
}; //key

 const delays = { // before piece drops by 1 row (seconds)
	start: 0.7,
	decrement: 0.003,
	min: 0.1
}; //delays

 const scoreRules = {
	addOnDrop: function(totalRemovedLineCount, currentScore) { return 10; },
	addOnRemovedLines: function(lineCount, totalRemovedLineCount, currentScore) { return 100 * Math.pow(2, lineCount - 1); }
}; //scoreRules

 const tetrominoColor = {
/* ── 	*/	I: "orange",
/* ─┐	*/	J: "orchid",
/*┌─ 	*/	L: "blue",
/* ☐	*/	O: "red",
/* _┌	*/	S: "lightskyblue",
/* ┬ 	*/	T: "yellow",   
/* ┐_	*/	Z: "lawngreen"
}; //tetrominoColor

 function TetrominoShape(size, blocks, color) { this.size = size; this.blocks = blocks; this.color = color; }
const tetrominoSet = [	new TetrominoShape(4, [0x0F00, 0x2222, 0x00F0, 0x4444], tetrominoColor.I),
			new TetrominoShape(3, [0x0E20, 0x44C0, 0x8E00, 0x6440], tetrominoColor.J),
			new TetrominoShape(3, [0x0E80, 0xC440, 0x2E00, 0x4460], tetrominoColor.L),
			new TetrominoShape(2, [0xCC00, 0xCC00, 0xCC00, 0xCC00], tetrominoColor.O),
			new TetrominoShape(3, [0x06C0, 0x8C40, 0x6C00, 0x4620], tetrominoColor.S),
			new TetrominoShape(3, [0x0E40, 0x4C40, 0x4E00, 0x4640], tetrominoColor.T),
			new TetrominoShape(3, [0x0C60, 0x4C80, 0xC600, 0x2640], tetrominoColor.Z)];

 //-------------------------------------------------------------------------
// tetramino:
//
// blocks: each element represents a rotation of the piece (0, 90, 180, 270)
//         each element is a 16 bit integer where the 16 bits represent
//         a 4x4 set of blocks, e.g. "J"-shaped tetrominoSet[1].blocks[1] = 0x44C0
//
//             0100 = 0x4 << 3 = 0x4000 
//             0100 = 0x4 << 2 = 0x0400
//             1100 = 0xC << 1 = 0x00C0
//             0000 = 0x0 << 0 = 0x0000
//                               ------
//                               0x44C0
//
//-------------------------------------------------------------------------

 </script>
<script>
    /*
Tetris on Canvas, v.3.0
Sergey A Kryukov, derived work
http://www.SAKryukov.org
http://www.codeproject.com/Members/SAKryukov

 Based on algorithms and working prototype developed by Jake Gordon:
http://codeincomplete.com
http://codeincomplete.com/posts/2011/10/10/javascript_tetris
https://github.com/jakesgordon/javascript-tetris

 License: MIT (http://en.wikipedia.org/wiki/MIT_License)

 S A Kryukov implemented:
Configurable game: board size, tetromino colors/shapes, score rules, timing
Auto-resizeable depending on the browser window size 
Drop of tetromino to bottom
Pause/continue
Help
FSM (states)
Fixed random tetromino generation
Javascript "strict mode"
Code improvements, exception handling, readability, fixes

 Published here:
http://www.codeproject.com/Articles/876475/Tetris-On-Canvas
*/

 "use strict";

 function Tetromino(shape, x, y, orientation) {
	this.shape = shape; //TetrominoShape
	this.x = x;
	this.y = y;
	this.orientation = orientation;
} //Tetromino

 Tetromino.prototype = {
	first: function (x0, y0, orientation, fn, doBreak) { // fn(x, y), accepts coordinates of each block, returns true to break
		let row = 0, col = 0, result = false, blocks = this.shape.blocks[orientation];
		for (let bit = 0x8000; bit > 0; bit = bit >> 1) {
			if (blocks & bit) {
				result = fn(x0 + col, y0 + row);
				if (doBreak && result)
					return result;
			} //if
			if (++col === 4) {
				col = 0;
				++row;
			} //if
		} //loop
		return result;
	}, //Tetromino.prototype.first
	all: function (fn) { // fn(x, y), accepts coordinates of each block
		this.first(this.x, this.y, this.orientation, fn, false); // no break
	} //Tetromino.prototype.all
} //Tetromino.prototype

 //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

 const layout = {

 	upcomingPreviewSize: 5, // size of upcoming preview (in blocks), for "upcoming" canvas
	spacing: { outsize: 18, inside: 24, border: 1 },
	statusWordSet: { start: "start", continue: "continue" },
	blockSize: 0,
	main: element("main"),
	left: element("left"),
	right: element("right"),
	board: element("board"),
	upcoming: element("upcoming"),

 	resizeBody: function () {
		this.left.style.paddingLeft = this.spacing.inside;
		this.left.style.paddingRight = this.spacing.inside;
		this.left.style.paddingTop = this.spacing.inside;
		this.left.style.paddingBottom = this.spacing.inside;
		this.right.style.paddingRight = this.spacing.inside;
		this.right.style.paddingTop = this.spacing.inside;
		this.right.style.paddingBottom = this.spacing.inside;
		let verticalSize = window.innerHeight - 2 * this.spacing.outsize - 2 * this.spacing.inside - 2 * this.spacing.border;
		this.blockSize = Math.floor(verticalSize / gameSizeInBlocks.y);
		let adjustedVerticalSize = this.blockSize * gameSizeInBlocks.y;
		this.board.style.height = adjustedVerticalSize;
		let boardWidth = this.blockSize * gameSizeInBlocks.x;
		this.board.style.width = boardWidth;
		let upcomingWidth = this.blockSize * this.upcomingPreviewSize;
		this.upcoming.style.height = upcomingWidth;
		this.upcoming.style.width = upcomingWidth;
		setText(rendering.statusVerb, this.statusWordSet.continue);
		let width1 = rendering.promptText.offsetWidth;
		setText(rendering.statusVerb, this.statusWordSet.start);
		let width2 = rendering.promptText.offsetWidth;
		this.left.style.width = maximum(upcomingWidth, width1, width2, upcomingWidth);
		this.main.style.borderWidth = this.spacing.border;
		this.main.style.marginTop = (window.innerHeight - this.main.offsetHeight) / 2;
		this.main.style.marginLeft = (window.innerWidth - this.main.offsetWidth) / 2;
		this.board.width = this.board.clientWidth;
		this.board.height = this.board.clientHeight;
		this.upcoming.width = this.upcoming.clientWidth;
		this.upcoming.height = this.upcoming.clientHeight;
		rendering.invalidate();
	}, //resizeBody
	resize: function () { try { this.resizeBody(); } catch (e) { showException(e); } }

 } //layout

 //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

 const game = {

 	actions: { rotate: 0, right: 1, down: 2, left: 3, bottom: 4 },
	orientation: { min: 0, max: 3 },
	states: { cancelled: 0, paused: 1, playing: 2, current: 0 },
	blocks: [],
	queue: [],
	duration: 0,	// of current game
	score: 0,
	rows: 0,	// removed rows
	delay: 0,	// before movind down by 1 row
	current: null,
	next: null,

 	setState: function (aState) { this.states.current = aState; rendering.invalidateState(); },
	startContinue: function () { if (this.states.current === this.states.cancelled) this.reset(); this.setState(this.states.playing); },
	cancel: function () { this.setState(this.states.cancelled); },
	pause: function () { this.setState(this.states.paused); },

 	willHitObstacle: function (tetromino, x0, y0, orientation) { // tentative move is blocked with some obstacle
		return tetromino.first(x0, y0, orientation, function (x, y) {
			if ((x < 0) || (x >= gameSizeInBlocks.x) || (y < 0) || (y >= gameSizeInBlocks.y) || game.getBlock(x, y))
				return true; // performance gain
		}, true);
	}, //willHitObstacle

 	randomTetromino: function () {
		const chosen = tetrominoSet[randomInt(0, tetrominoSet.length - 1)];
		return new Tetromino(chosen, randomInt(0, gameSizeInBlocks.x - chosen.size), 0, 0);
	}, //randomTetromino

 	setScore: function (n) { this.score = n; rendering.invalidateScore(); },
	addScore: function (n) { this.setScore(this.score + n); },
	setRows: function (n) { this.rows = n; this.delay = Math.max(delays.min, delays.start - (delays.decrement * this.rows)); rendering.invalidateRows(); },
	addRows: function (n) { this.setRows(this.rows + n); },
	getBlock: function (x, y) { return (this.blocks && this.blocks[x] ? this.blocks[x][y] : null); },
	setBlock: function (x, y, shape) { this.blocks[x] = this.blocks[x] || []; this.blocks[x][y] = shape; rendering.invalidate(); },
	clearQueue: function () { this.queue = []; },
	setCurrentTetromino: function (t) { this.current = t || this.randomTetromino(); rendering.invalidate(); },
	setNextTetromino: function (t) { this.next = t || this.randomTetromino(); rendering.invalidateUpcoming(); },

 	reset: function () {
		this.duration = 0;
		this.setScore(0);
		this.setRows(0);
		this.blocks = []; rendering.invalidate();
		this.clearQueue();
		this.setCurrentTetromino(this.next);
		this.setNextTetromino();
	}, //reset

 	update: function (dTime) {
		if (this.states.current != this.states.playing) return;
		this.handle(this.queue.shift());
		this.duration += dTime;
		if (this.duration > this.delay) { this.duration -= this.delay; this.drop(); }
	}, //update 

 	move: function (direction) {
		let x = this.current.x, y = this.current.y;
		switch (direction) {
			case this.actions.right: x += 1; break;
			case this.actions.left: x -= 1; break;
			case this.actions.down: y += 1; break;
		} //switch
		if (!this.willHitObstacle(this.current, x, y, this.current.orientation)) {
			this.current.x = x;
			this.current.y = y;
			rendering.invalidate();
			return true;
		} else
			return false;
	}, //move

 	rotate: function () {
		const newOrientation = (this.current.orientation === this.orientation.max ? this.orientation.min : this.current.orientation + 1);
		if (this.willHitObstacle(this.current, this.current.x, this.current.y, newOrientation)) return;
		this.current.orientation = newOrientation;
		rendering.invalidate();
	}, //rotate

 	drop: function () {
		if (this.move(this.actions.down)) return;
		this.addScore(scoreRules.addOnDrop(this.rows, this.score));
		this.dropTetromino();
		this.removeLines();
		this.setCurrentTetromino(this.next);
		this.setNextTetromino(this.randomTetromino());
		this.clearQueue();
		if (this.willHitObstacle(this.current, this.current.x, this.current.y, this.current.orientation))
			this.cancel();
	}, //drop

 	dropTetromino: function () {
		this.current.all(function (x, y) {
			game.setBlock(x, y, game.current.shape);
		});
	}, //dropTetromino

 	dropDown: function () {
		while (this.move(this.actions.down)) { }
	}, //dropDown

 	removeLine: function (n) {
		for (let y = n; y >= 0; --y)
			for (let x = 0; x < gameSizeInBlocks.x; ++x)
				this.setBlock(x, y, (y === 0) ? null : this.getBlock(x, y - 1));
	}, //removeLine

 	removeLines: function () {
		let complete, n = 0;
		for (let y = gameSizeInBlocks.y; y > 0; --y) {
			complete = true;
			for (let x = 0; x < gameSizeInBlocks.x; ++x)
				if (!this.getBlock(x, y))
					complete = false;
			if (complete) {
				this.removeLine(y);
				y += 1; // recheck same line
				++n;
			} //if
		} //loop y
		if (n > 0) {
			this.addRows(n);
			this.addScore(scoreRules.addOnRemovedLines(n, this.rows, this.score));
		} //if n
	}, //removeLines

 	handle: function (action) {
		switch (action) {
			case this.actions.left: this.move(action); break;
			case this.actions.right: this.move(action); break;
			case this.actions.rotate: this.rotate(); break;
			case this.actions.down: this.drop(); break;
			case this.actions.bottom: this.dropDown(); break;
		} //switch
	}, //handle

 	clickBody: function () {
		if (this.states.current === this.states.playing)
			this.pause();
		else
			this.startContinue();
	}, //clickBody
	click: function (event) { try { this.clickBody(event); } catch (e) { showException(e); } },
	keydownBody: function (event) {
		if (event.keyCode === key.help) {
			rendering.help();
			event.preventDefault();
			return;
		} //if help		
		let handled = false;
		if (this.states.current === this.states.playing) {
			switch (event.keyCode) {
				case key.left: this.queue.push(this.actions.left); handled = true; break;
				case key.right: this.queue.push(this.actions.right); handled = true; break;
				case key.rotate: this.queue.push(this.actions.rotate); handled = true; break;
				case key.down: this.queue.push(this.actions.down); handled = true; break;
				case key.dropDown: this.queue.push(this.actions.bottom); handled = true; break;
				case key.cancel: this.cancel(); handled = true; break;
				case key.start: this.pause(); handled = true; break;
			} //switch 
		} else if (event.keyCode === key.start) {
			this.startContinue();
			handled = true;
		} //if
		if (handled)
			event.preventDefault(); // prevent arrow keys from scrolling the page (supported in IE9+ and all other browsers)
	}, //keydownBody
	keydown: function (event) { try { this.keydownBody(event); } catch (e) { showException(e); } }

 } //game

 //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

 const rendering = {

 	promptText: element("prompt"),
	scoreText: element("score"),
	rowsText: element("rows"),
	pausedText: element("paused"),
	helpWindow: element("help"),
	helpImageHelp: element("id.help"),
	helpImageExit: element("id.exit"),	
    badBrowser: element("bad-browser"),
	statusVerb: element("statusVerb"),
	boardContext: layout.board.getContext("2d"),
	upcomingContext: layout.upcoming.getContext("2d"),
	invalid: { board: true, upcoming: true, score: true, rows: true, state: true },
	invalidate: function () { this.invalid.board = true; },
	invalidateUpcoming: function () { this.invalid.upcoming = true; },
	invalidateScore: function () { this.invalid.score = true; },
	invalidateRows: function () { this.invalid.rows = true; },
	invalidateState: function () { this.invalid.state = true; },
	showingHelp: false,

 	showHelpImage: function(doShow) {
		if (doShow) {
			this.helpImageHelp.style.display = "inline"; 
			this.helpImageExit.style.display = "none"; 
		} else {
			this.helpImageHelp.style.display = "none"; 
			this.helpImageExit.style.display = "inline"; 
		} //if
	}, //showHelpImage
	initializeHelp: function () {
		const versionElement = element("version");
        versionElement.textContent = version;
		hide(this.helpWindow);
		hide(this.badBrowser, true);
	}, //initializeHelp
	help: function () {
		this.showHelpImage(this.showingHelp);		
		setVisibility(this.helpWindow, this.showingHelp = !this.showingHelp);
	}, //help

 	draw: function () {
		const drawTetromino = function (context, tetromino) {
			tetromino.all(function (x, y) {
				drawBlock(context, x, y, tetromino.shape.color);
			});
		}; //drawTetromino
		const drawTetrominoAt = function (context, tetromino, location) {
			tetromino.all(function (x, y) {
				drawBlock(context, x + location.x - tetromino.x, y + location.y - tetromino.y, tetromino.shape.color);
			});
		}; //drawTetrominoAt
		const drawBlock = function (context, x, y, color) {
			context.fillStyle = color;
			context.fillRect(x * layout.blockSize, y * layout.blockSize, layout.blockSize, layout.blockSize);
			context.strokeRect(x * layout.blockSize, y * layout.blockSize, layout.blockSize, layout.blockSize)
		}; //drawBlock
		const finerLines = function (context) {
			context.lineWidth = 1;
			context.translate(0.5, 0.5);
		}; //finerLines
		const drawUpcoming = function (context) {
			if (!this.invalid.upcoming) return;
			if (game.states.current != game.states.playing) return;
			const padding = (layout.upcomingPreviewSize - game.next.shape.size) / 2; // half-arsed attempt at centering next tetromino display
			context.save();
			finerLines(context);
			context.clearRect(-1, -1, layout.upcomingPreviewSize * layout.blockSize + 1, layout.upcomingPreviewSize * layout.blockSize + 1);
			drawTetrominoAt(context, game.next, { x: padding, y: padding });
			context.restore();
			this.invalid.upcoming = false;
		}; //drawUpcoming
		const drawBoard = function (context) {
			if (!this.invalid.board) return;
			context.save();
			finerLines(context);
			context.clearRect(-1, -1, context.canvas.width + 1, context.canvas.height + 1);
			if (game.states.current === game.states.playing)
				drawTetromino(context, game.current);
			let block;
			for (let y = 0; y < gameSizeInBlocks.y; y++)
				for (let x = 0; x < gameSizeInBlocks.x; x++)
					if (block = game.getBlock(x, y))
						drawBlock(context, x, y, block.color);
			context.strokeRect(0, 0, context.canvas.width - 1, context.canvas.height - 1); // board boundary
			context.restore();
			this.invalid.board = false;
		}; //drawBoard
		const drawScore = function () {
			if (!this.invalid.score) return;
			setText(this.scoreText, game.score);
			this.invalid.score = false;
		}; //drawScore
		const drawRows = function () {
			if (!this.invalid.rows) return;
			setText(this.rowsText, game.rows);
			this.invalid.rows = false;
		}; //drawRows
		const drawState = function () {
			if (!this.invalid.state) return;
			setText(rendering.statusVerb, game.states.current === game.states.paused ? layout.statusWordSet.continue : layout.statusWordSet.start);
			setVisibility(this.pausedText, game.states.current === game.states.paused);
			setVisibility(this.promptText, game.states.current != game.states.playing);
			this.invalid.state = false;
		}; //drawState
		drawBoard.call(this, this.boardContext);
		drawUpcoming.call(this, this.upcomingContext);
		drawScore.call(this);
		drawRows.call(this);
		drawState.call(this);
	} //draw

 } //rendering

 //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

 function randomInt(min, max) { return Math.floor(Math.random() * (max - min + 1)) + min; }
function element(id) { return document.getElementById(id); }
function now() { return new Date().getTime(); }
function hide(object, noDisplay) { object.style.visibility = "hidden"; if (noDisplay) object.style.display = "none"; }
function show(object) { object.style.visibility = null; }
function setVisibility(object, visible) { if (visible) show(object); else hide(object); }
function setText(object, text) { object.innerHTML = text; }
function maximum() {
	let big = Number.NEGATIVE_INFINITY;
	for (let argument of arguments) {
		let value = arguments;
		if (value > big)
			big = value;
	} //loop
	return big;
} //maximum
function showException(exception) {
	//return;
	alert(exception.name + ":\n" + exception.message +
		"\n" + "\nLine: " + exception.lineNumber + "; column: " + (exception.columnNumber + 1) +
		"\n\n" + exception.stack);
} //showException

 try {
	(function () {
		if (!window.requestAnimationFrame) // http://paulirish.com/2011/requestanimationframe-for-smart-animating/
			window.requestAnimationFrame =
				window.webkitRequestAnimationFrame ||
				window.mozRequestAnimationFrame ||
				window.oRequestAnimationFrame ||
				window.msRequestAnimationFrame ||
				function (callback, element) { window.setTimeout(callback, 1000 / 60); }
		rendering.initializeHelp();
		layout.resize();
		game.reset();
		window.onresize = function () { layout.resize(); };
		document.onkeydown = function (event) { game.keydown(event); };
		window.onclick = function () { game.click(); };
		rendering.helpWindow.onclick = function () { rendering.help(); };
		rendering.helpImageHelp.onclick = function () { rendering.help(); };
		rendering.helpImageExit.onclick = function () { rendering.help(); };
		let after, before = now();
		(function frame() {
			after = now();
			game.update(Math.min(1, (after - before) / 1000.0));
			rendering.draw();
			before = after;
			requestAnimationFrame(frame, layout.board);
		})()
	})();
} catch (e) { showException(e); }

 </script>

 </body>
</html>>&rarr;</big>, <big>&darr;</big>: move</p>
<p><big>&uarr;</big>: rotate <big>&orarr;</big></p>
<p>Space: drop down</p>
<p>Enter: start/pause/continue game</p>
<p>Escape: cancel game</p>
<p>F1: show/hide help</p><hr/>
