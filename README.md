# Choir Music Generation with LSTM

Günay Eser - Boğaziçi University Computational Science and Engineering

**Abstract**

Music generation has become an area that is researched with a signiﬁcant pace only recently. Generating music has many challenging points to overcome and it is a long way to obtain a piece that is so close to a humancomposedone.Musicgenerallycontainsseveraltracks, each of which has different note pattern, style, instrumental characteristics and emotion. When combined, these tracks create a harmonic and tuneful music. So far, papers on music generation were focused on generating instrumental music. In this paper, we propose a new type of music generation, Choral music. Choral musicisconstitutedfromdifferentvocalgroupslikeSoprano, Alto, Tenor and Bass. Sometimes these groups get separated into smaller groups like (Soprano 1 and Soprano 2) and each individual group has a particular trackinthesongtosing.Targetofthispaper’sapproach istocomposetracksfor4singergroups(Soprano,Alto, Tenor, Bass) that is pleasant to hear when combined and transformed into a choir song. We use word2vec word embbedding for vectorize notes and chords, then use LSTM Network for generate new trakcs. Our approach gives better results in generation process when the chords are considered as words instead of notes.
