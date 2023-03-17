# Ordinaries

Ordinaries is a simple format for inscribing text data into ordinals on the blockchain. The format consists of a set of keys that define the information being inscribed, as well as any relevant metadata. The format is designed to be flexible and extensible, allowing it to be used in a wide variety of applications.

## Potential Applications

Here are a few examples of the potential applications for the Ordinaries format:

    Books: Each chapter of a book can be represented by an Ordinary object, with the extend key used to connect each chapter to the previous one.

    Academic Credentials: Each credential can be represented by an Ordinary object, with fields for the name of the credential, the issuing institution, and the recipient's name and other relevant information.

    Music: Playlists of music can be created using Ordinaries, with each song represented by an Ordinary object.

    Voting Systems: Votes can be represented by Ordinaries, with fields for the voter's information, the vote itself, and any additional information.

These are just a few examples of the potential applications for the Ordinaries format. The flexibility and simplicity of the format make it ideal for a wide variety of use cases, limited only by the creativity and imagination of its users.

# Ordinary Implementation Specifications (OIS)

The Ordinary Implementation Specifications (OIS) define the specific keys and values that can be used in an Ordinary object. Each OIS is identified by a unique ois_id value, which is used to indicate the specific use case for the object.

The OIS specification is designed to be extensible, allowing new keys and values to be added as needed. This flexibility allows the Ordinaries format to be used in a wide variety of applications.

# Available OIS

Here are the OIS currently available:

| OIS | Description |
|-----|-------------|
|[OIS-00](OIS-00.md)| The basic Ordinary format, consisting of the ois_id and extend keys.|
|[OIS-01](OIS-01.md)| Playlists, consisting of fields for the name of the playlist, a description, and an array of songs.|

Additional OIS will be added as needed, as new use cases are identified.
