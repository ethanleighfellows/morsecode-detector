MORSE CODE DETECTION DEMO

This is a quick and simple demonstration showing how easily Morse-code–encoded inputs can be detected using a very basic algorithm.

Even simple heuristics—such as checking for inputs composed exclusively of dots, dashes, and valid spacing patterns—are sufficient to
reliably flag Morse sequences. Because of this, Morse-based obfuscation is trivial to identify and normalize before additional
processing.

This demonstration is intentionally lightweight, but it highlights how straightforward it is to surface encoded inputs as part of
a broader input-sanitization or preprocessing pipeline.
