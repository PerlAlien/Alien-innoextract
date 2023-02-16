# NAME

Alien::innoextract - Find or build innoextract

# SYNOPSIS

Command line tool:

    use Alien::innoextract;
    use Env qw( @PATH );

    unshift @PATH, Alien::innoextract->bin_dir;

# DESCRIPTION

This distribution provides innoextract so that it can be used by other
Perl distributions that are on CPAN.  It does this by first trying to
detect an existing install of innoextract on your system.  If found it
will use that.  If it cannot be found, the source code will be downloaded
from the internet and it will be installed in a private share location
for the use of other modules.

# SEE ALSO

- [Alien](https://metacpan.org/pod/Alien)

    Documentation on the Alien concept itself.

- [Alien::Base](https://metacpan.org/pod/Alien%3A%3ABase)

    The base class for this Alien.

- [Alien::Build::Manual::AlienUser](https://metacpan.org/pod/Alien%3A%3ABuild%3A%3AManual%3A%3AAlienUser)

    Detailed manual for users of Alien classes.
