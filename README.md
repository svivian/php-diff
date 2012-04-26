PHP Diff
========

Diff algorithm written in PHP. Usage:

	<?php
	$original = 'The quick brown fox jumps over the lazy dog.';
	$new = 'The cute yellow Pikachu jumps over the fiery Charizard.';
    echo diff_string::compare( $original, $new )

Outputs:

    The <del>quick </del><del>brown </del><del>fox </del><ins>cute </ins><ins>yellow </ins><ins>Pikachu </ins> jumps  over  the <del>lazy </del><del>dog.</del><ins>fiery </ins><ins>Charizard.</ins>

