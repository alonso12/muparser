# muparser
official repository of the muparser fast math parser library



Compile warnings when compiling with mingw gcc/c++.

"std::auto_ptr" is depreciated and should be replaced with "std::unique_ptr".

muParserToken.h
about line 72
//*** ***
//std::auto_ptr m_pCallback;
std::unique_ptr m_pCallback;
//*** ***

muParserBase.h
about line 292
//*** ***
//std::auto_ptr<token_reader_type> m_pTokenReader; ///< Managed pointer to the token reader object.
std::unique_ptr<token_reader_type> m_pTokenReader; ///< Managed pointer to the token reader object.
//*** ***
