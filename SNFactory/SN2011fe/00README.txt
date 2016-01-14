
2013-02-05
----------

Contact: Rui Pereira <rui.pereira@in2p3.fr>

This distribution contains 32 spectra, in either ascii table (*.dat) or
1D FITS (*.fit) formats. All files can be checked for consistency using:

   sha1sum -c checksum.sha1

The ascii tables contain 3 space delimited columns, respectively
wavelength, flux and variance (photon noise). The 1D FITS files contain
the flux in the primary extension and the variance as a separate
extension.  The spectra have not been redshift-corrected, but have been
corrected for Milky Way extinction as described in the paper.  The
FLUXERR keyword represents the (achromatic) absolute flux calibration
accuracy [mag] as estimated by the calibration pipeline, and should be
added to the error of any synthetic magnitudes (not colors) computed
using the spectra. The filename notation is 11fe[PM]xxx.*, where [PM]
stands for Plus or Minus and xxx is the phase of observation, in days
relative to B-band maximum, times 10, eg.:

   11feM083.fit = - 8.3 d
   11feP217.fit = +21.7 d

The data contained in this distribution complement a publication from
the Nearby Supernova Factory (SNfactory).  The acquisition, reduction,
and analysis of these data are fully described in that work.  SNfactory
is providing these data to be used by other scientists for the purpose
of furthering their analyses.  Work benefitting from the use of these
data should include the following citation, conveniently included here
as an aastex bibliography entry that may be cut and pasted into a
manuscript:

\bibitem[Pereira \emph{et al.}(2013)]{Pereira2013} Pereira, R., et al.\ 2013,
\aap, 554, A27

Alternatively, the following bibtex entry may be used:

@ARTICLE{2013A&A...554A..27P,
   author = {{Pereira}, R. and {Thomas}, R.~C. and {Aldering}, G. and {Antilogus}, P. and
        {Baltay}, C. and {Benitez-Herrera}, S. and {Bongard}, S. and
        {Buton}, C. and {Canto}, A. and {Cellier-Holzem}, F. and {Chen}, J. and
        {Childress}, M. and {Chotard}, N. and {Copin}, Y. and {Fakhouri}, H.~K. and
        {Fink}, M. and {Fouchez}, D. and {Gangler}, E. and {Guy}, J. and
        {Hillebrandt}, W. and {Hsiao}, E.~Y. and {Kerschhaggl}, M. and
        {Kowalski}, M. and {Kromer}, M. and {Nordin}, J. and {Nugent}, P. and
        {Paech}, K. and {Pain}, R. and {P{\'e}contal}, E. and {Perlmutter}, S. and
        {Rabinowitz}, D. and {Rigault}, M. and {Runge}, K. and {Saunders}, C. and
        {Smadja}, G. and {Tao}, C. and {Taubenberger}, S. and {Tilquin}, A. and
        {Wu}, C.},
    title = "{Spectrophotometric time series of SN 2011fe from the Nearby Supernova Factory}",
  journal = {\aap},
archivePrefix = "arXiv",
   eprint = {1302.1292},
 primaryClass = "astro-ph.CO",
 keywords = {supernovae: individual: SN 2011fe},
     year = 2013,
    month = jun,
   volume = 554,
      eid = {A27},
    pages = {A27},
      doi = {10.1051/0004-6361/201221008},
   adsurl = {http://adsabs.harvard.edu/abs/2013A%26A...554A..27P},
  adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}

*** PLEASE BE ADVISED *** PLEASE BE ADVISED *** PLEASE BE ADVISED ***

Some or all of the data included here will eventually be superceded by
improved reductions in a subsequent SNfactory data release.  For that
reason, we suggest that users occasionally confirm that they have the
most recent version of the data by checking the SNfactory website.  We
would also recommend that people looking to get the data for the first
time get it from the website directly.

Please do not publicly re-host the data on the web somewhere else
without checking with us first.  We would like it to be clear to
everyone the authoritative reductions are always available at the
SNfactory project web site. 
