
# Properties #

## General ##
| **Property** | **Description** |
|:-------------|:----------------|
|`Count`|Count of objects available in this stream|
|`Status`|bit field (0=`IsAccepted`, 1=`IsFilled`, 2=`IsUpdated`, 3=IsFinished)|
|`StreamCount`|Count of streams of that kind available|
|`StreamKind`|Stream type name|
|`StreamKind/String`|Stream type name|
|`StreamKindID`|Number of the stream (base=0)|
|`StreamKindPos`|When multiple streams, number of the stream (base=1)|
|`StreamOrder`|Stream order in the file, whatever is the kind of stream (base=0)|
|`FirstPacketOrder`|Order of the first fully decodable packet met in the file, whatever is the kind of stream (base=0)|
|`Inform`|Last Inform call|
|`ID`|The ID for this stream in this file|
|`ID/String`|The ID for this stream in this file|
|`UniqueID`|The unique ID for this stream, should be copied with stream copy|
|`UniqueID/String`|The unique ID for this stream, should be copied with stream copy|
|`MenuID`|The menu ID for this stream in this file|
|`MenuID/String`|The menu ID for this stream in this file|
|`GeneralCount`|Number of general streams|
|`VideoCount`|Number of video streams|
|`AudioCount`|Number of audio streams|
|`TextCount`|Number of text streams|
|`OtherCount`|Number of other streams|
|`ImageCount`|Number of image streams|
|`MenuCount`|Number of menu streams|
|`Video_Format_List`|Video Codecs in this file, separated by /|
|`Video_Format_WithHint_Lis`|Video Codecs in this file with popular name (hint), separated by /|
|`Video_Codec_List`|Deprecated, do not use in new projects|
|`Video_Language_List`|Video languagesin this file, full names, separated by /|
|`Audio_Format_List`|Audio Codecs in this file,separated by /|
|`Audio_Format_WithHint_Lis`|Audio Codecs in this file with popular name (hint), separated by /|
|`Audio_Codec_List`|Deprecated, do not use in new projects|
|`Audio_Language_List`|Audio languages in this file separated by /|
|`Text_Format_List`|Text Codecs in this file, separated by /|
|`Text_Format_WithHint_List`|Text Codecs in this file with popular name (hint),separated by /|
|`Text_Codec_List`|Deprecated, do not use in new projects|
|`Text_Language_List`|Text languages in this file, separated by /|
|`Other_Format_List`|Other formats in this file, separated by /|
|`Other_Format_WithHint_Lis`|Other formats in this file with popular name (hint), separated by /|
|`Other_Codec_List`|Deprecated, do not use in new projects|
|`Other_Language_List`|Chapters languages in this file, separated by /|
|`Image_Format_List`|Image Codecs in this file, separated by /|
|`Image_Format_WithHint_Lis`|Image Codecs in this file with popular name (hint), separated by /|
|`Image_Codec_List`|Deprecated, do not use in new projects|
|`Image_Language_List`|Image languages in this file, separated by /|
|`Menu_Format_List`|Menu Codecsin this file, separated by /|
|`Menu_Format_WithHint_List`|Menu Codecs in this file with popular name (hint),separated by /|
|`Menu_Codec_List`|Deprecated, do not use in new projects|
|`Menu_Language_List`|Menu languages in this file, separated by /|
|`CompleteName`|Complete name (Folder+Name+Extension)|
|`FolderName`|Folder name only|
|`FileName`|File name only|
|`FileExtension`|File extension only|
|`CompleteName_Last`|Complete name (Folder+Name+Extension) of the last file (in the case of a sequence of files)|
|`FolderName_Last`|Folder name only of the last file (in the case of a sequence of files)|
|`FileName_Last`|File name only of the last file (in the case of a sequence of files)|
|`FileExtension_Last`|File extension only of the last file (in the case of a sequence of files)|
|`Format` |Format used|
|`Format/String`|Deprecated, do not use in new projects|
|`Format/Info`|Info about this Format|
|`Format/Url`|Link to a description of this format|
|`Format/Extensions`|Known extensions of this format|
|`Format_Commercial`|Commercial name used by vendor for theses setings or Format field if there is no difference|
|`Format_Commercial_IfAny`|Commercial name used by vendor for theses setings if there is one|
|`Format_Version`|Version of this format|
|`Format_Profile`|Profile of the Format|
|`Format_Compression`|Compression method used|
|`Format_Settings`|Settings needed for decoder used|
|`InternetMediaType`|Internet Media Type (aka MIME Type, Content-Type)|
|`CodecID`|Codec ID (found in some containers)|
|`CodecID/String`|Codec ID (found in some containers)|
|`CodecID/Info`|Info about this codec|
|`CodecID/Hint`|A hint/popular name for this codec|
|`CodecID/Url`|A link to more details about this codec ID|
|`CodecID_Description`|Manual description given by the container|
|`Interleaved`|If Audio and video are muxed|
|`Codec`|Deprecated, do not use in new projects|
|`Codec/String`|Deprecated, do not use in new projects|
|`Codec/Info`|Deprecated, do not use in new projects|
|`Codec/Url`|Deprecated, do not use in new projects|
|`Codec/Extensions`|Deprecated, do not use in new projects|
|`Codec_Settings`|Deprecated, do not use in new projects|
|`Codec_Settings_Automatic`|Deprecated, do not use in new projects|
|`FileSize`|File size in bytes|
|`FileSize/String`|File size (with measure)|
|`FileSize/String1`|File size (with measure, 1 digit mini)|
|`FileSize/String2`|File size (with measure, 2 digit mini)|
|`FileSize/String3`|File size (with measure, 3 digit mini)|
|`FileSize/String4`|File size (with measure, 4 digit mini)|
|`Duration`|Play time of the stream in ms|
|`Duration/String`|Play time in format: `XXx YYy` only, `YYy` omitted if zero|
|`Duration/String1`|Play time in format: `HHh MMmn SSs MMMms`, `XX` omited if zero|
|`Duration/String2`|Play time in format: `XXx YYy` only, `YYy` omited if zero|
|`Duration/String3`|Play time in format: `HH:MM:SS.MMM`|
|`Duration_Start`|  |
|`Duration_End`|  |
|`OverallBitRate_Mode`|Bit rate mode of all streams (VBR, CBR)|
|`OverallBitRate_Mode/Strin`|Bit rate mode of all streams (Variable, Constant)|
|`OverallBitRate`|Bit rate of all streams in bps|
|`OverallBitRate/String`|Bit rate of all streams (with measure)|
|`OverallBitRate_Minimum`|Minimum Bit rate in bps|
|`OverallBitRate_Minimum/St`|Minimum Bit rate (with measurement)|
|`OverallBitRate_Nominal`|Nominal Bit rate in bps|
|`OverallBitRate_Nominal/St`|Nominal Bit rate (with measurement)|
|`OverallBitRate_Maximum`|Maximum Bit rate in bps|
|`OverallBitRate_Maximum/St`|Maximum Bit rate (with measurement)|
|`Delay`|Delay fixed in the stream (relative) IN MS|
|`Delay/String`|Delay with measurement|
|`Delay/String1`|Delay with measurement|
|`Delay/String2`|Delay with measurement|
|`Delay/String3`|format: `HH:MM:SS.MMM`|
|`StreamSize`|Stream size in bytes|
|`StreamSize/String`|  |
|`StreamSize/String1`|  |
|`StreamSize/String2`|  |
|`StreamSize/String3`|  |
|`StreamSize/String4`|  |
|`StreamSize/String5`|With proportion|
|`StreamSize_Proportion`|Stream size divided by file size|
|`HeaderSize`|  |
|`DataSize`|  |
|`FooterSize`|  |
|`IsStreamable`|  |
|`Album_ReplayGain_Gain`|The gain to apply to reach 89dB SPL on playback|
|`Album_ReplayGain_Gain/String`|  |
|`Album_ReplayGain_Peak`|The maximum absolute peak value of the item|
|`Encryption`|  |
|`Title`|(Generic)Title of file|
|`Title/More`|(Generic)More info about the title of file|
|`Title/Url`|(Generic)Url|
|`Domain`|Univers movies belong to, e.g. Starwars, Stargate, Buffy, Dragonballs|
|`Collection`|Name of the series, e.g. Starwars movies, Stargate SG-1, Stargate Atlantis, Buffy, Angel|
|`Season`|Name of the season, e.g. Strawars first Trilogy, Season 1|
|`Season_Position`|Number of the Season|
|`Season_Position_Total`|Place of the season e.g. 2 of 7|
|`Movie`|Name of the movie. Eg: `Starwars, a new hope`|
|`Movie/More`|More infos about the movie|
|`Movie/Country`|Country, where the movie was procuced|
|`Movie/Url`|Homepage for the movie|
|`Album`|Name of an audio-album. Eg: `The joshua tree`|
|`Album/More`|More infos about the album|
|`Album/Sort`|  |
|`Album/Performer`|Album performer/artist of this file|
|`Album/Performer/Sort`|  |
|`Album/Performer/Url`|Homepage of the album performer/artist|
|`Comic`|Name of the comic.|
|`Comic/More`|  |
|`Comic/Position_Total`|  |
|`Part`|Name of the part. e.g. CD1, CD2|
|`Part/Position`|Number of the part|
|`Part/Position_Total`|Place of the part e.g. 2 of 3|
|`Track`|Name of the track. e.g. track1, track 2|
|`Track/More`|More infos about the track|
|`Track/Url`|Link to a site about this track|
|`Track/Sort`|  |
|`Track/Position`|Number of this track|
|`Track/Position_Total`|Place of this track, e.g. 3 of 15|
|`Grouping`|iTunes grouping|
|`Chapter`|Name of the chapter.|
|`SubTrack`|Name of the subtrack.|
|`Original/Album`|Original name of album, serie...|
|`Original/Movie`|Original name of the movie|
|`Original/Part`|Original name of the part in the original support|
|`Original/Track`|Original name of the track in the original support|
|`Compilation`|iTunes compilation|
|`Compilation/String`|iTunes compilation|
|`Performer`|Main performer/artist of this file|
|`Performer/Sort`|  |
|`Performer/Url`|Homepage of the performer/artist|
|`Original/Performer`|Original artist(s)/performer(s).|
|`Accompaniment`|Band/orchestra/accompaniment/musician.|
|`Composer`|Name of the original composer.|
|`Composer/Nationality`|Nationality of the main composer of the item, mostly for classical music.|
|`Arranger`|The person who arranged the piece. e.g. Ravel.|
|`Lyricist`|The person who wrote the lyrics for a musical item.|
|`Original/Lyricist`|Original lyricist(s)/text writer(s).|
|`Conductor`|The artist(s) who performed the work. In classical music this would be the conductor, orchestra, soloists.|
|`Director`|Name of the director.|
|`AssistantDirector`|Name of the assistant director.|
|`DirectorOfPhotography`|The name of the director of photography, also known as cinematographer.|
|`SoundEngineer`|The name of the sound engineer or sound recordist.|
|`ArtDirector`|The person who oversees the artists and craftspeople who build the sets.|
|`ProductionDesigner`|The person responsible for designing the Overall visual appearance of a movie.|
|`Choregrapher`|The name of the choregrapher.|
|`CostumeDesigner`|The name of the costume designer.|
|`Actor`|Real name of an actor or actress playing a role in the movie.|
|`Actor_Character`|Name of the character an actor or actress plays in this movie.|
|`WrittenBy`|The author of the story or script.|
|`ScreenplayBy`|The author of the screenplay or scenario (used for movies and TV shows).|
|`EditedBy`|Editors name|
|`CommissionedBy`|name of the person or organization that commissioned the subject of the file|
|`Producer`|Name of the producer of the movie.|
|`CoProducer`|The name of a co-producer.|
|`ExecutiveProducer`|The name of an executive producer.|
|`MusicBy`|Main music-artist for a movie|
|`DistributedBy`|Company the item is mainly distributed by |
|`OriginalSourceForm/Distri`|Name of the person or organization who supplied the original subject|
|`MasteredBy`|The engineer who mastered the content for a physical medium or for digital distribution.|
|`EncodedBy`|Name of the person or organisation that encoded/ripped the audio file.|
|`RemixedBy`|Name of the artist(s), that interpreted, remixed, or otherwise modified the item.|
|`ProductionStudio`|Main production studio |
|`ThanksTo`|A very general tag for everyone else that wants to be listed.|
|`Publisher`|Name of the organization publishing the album (i.e. the 'record label') or movie.|
|`Publisher/URL`|Publishers official webpage.|
|`Label`|Brand or trademark associated with the marketing of music recordings and music videos.|
|`Genre`|The main genre of the audio or video. e.g. classical, ambient-house, synthpop, sci-fi, drama, etc.|
|`Mood`|Intended to reflect the mood of the item with a few keywords, e.g. Romantic, Sad, Uplifting, etc.|
|`ContentType`|The type of the item. e.g. Documentary, Feature Film, Cartoon, Music Video, Music, Sound FX, etc.|
|`Subject`|Describes the topic of the file, such as Aerial view of Seattle..|
|`Description`|A short description of the contents, such as Two birds flying.|
|`Keywords`|Keywords to the item separated by a comma, used for searching.|
|`Summary`|A plot outline or a summary of the story.|
|`Synopsis`|A description of the story line of the item.|
|`Period`|Describes the period that the piece is from or about. e.g. Renaissance.|
|`LawRating`|Depending on the country it's the format of the rating of a movie (P, R, X in the USA, an age in other countries or a URI defining a logo).|
|`LawRating_Reason`|Reason for the law rating|
|`ICRA`|The ICRA rating. (Previously RSACi)|
|`Released_Date`|The date/year that the item was released.|
|`Original/Released_Date`|The date/year that the item was originaly released.|
|`Recorded_Date`|The time/date/year that the recording began.|
|`Encoded_Date`|The time/date/year that the encoding of this item was completed began.|
|`Tagged_Date`|The time/date/year that the tags were done for this item.|
|`Written_Date`|The time/date/year that the composition of the music/script began.|
|`Mastered_Date`|The time/date/year that the item was tranfered to a digitalmedium.|
|`File_Created_Date`|The time that the file was created on the file system|
|`File_Created_Date_Local`|The time that the file was created on the file system (Warning: this field depends of local configuration, do not use it in an international database)|
|`File_Modified_Date`|The time that the file was modified on the file system|
|`File_Modified_Date_Local`|The time that the file was modified on the file system (Warning: this field depends of local configuration, do not use it in an international database)|
|`Recorded_Location`|Location where track was recorded. (See COMPOSITION\_LOCATION for format)|
|`Written_Location`|Location that the item was originaly designed/written. Information should be stored in the following format: country code, state/province, city where the coutry code is the same 2 octets as in Internet domains, or possibly ISO-3166. e.g. US, Texas, Austin or US, , Austin.|
|`Archival_Location`|Location, where an item is archived, e.eg. Louvre,Paris,France|
|`Encoded_Application`|Name of the software package used to create the file, such as Microsoft WaveEdit.|
|`Encoded_Application/Url`|Name of the software package used to create the file, such as Microsoft WaveEdit.|
|`Encoded_Library`|Software used to create the file|
|`Encoded_Library/String`|Software used to create the file|
|`Encoded_Library/Name`|Name of the the encoding-software|
|`Encoded_Library/Version`|Version of encoding-software|
|`Encoded_Library/Date`|Release date of software|
|`Encoded_Library_Settings`|Parameters used by the software|
|`Cropped`|Describes whether an image has been cropped and, if so, how it was cropped.|
|`Dimensions`|Specifies the size of the original subject of the file. eg 8.5 in h, 11 in w|
|`DotsPerInch`|Stores dots per inch setting of the digitizer used to produce the file|
|`Lightness`|Describes the changes in lightness settings on the digitizer required to produce the file|
|`OriginalSourceMedium`|Original medium of the material, e.g. vinyl, Audio-CD, Super8 or BetaMax|
|`OriginalSourceForm`|Original form of the material, e.g. slide, paper, map|
|`OriginalSourceForm/NumCol`|Number of colors requested when digitizing, e.g. 256 for images or 32 bit RGB for video|
|`OriginalSourceForm/Name`|Name of the product the file was originally intended for|
|`OriginalSourceForm/Croppe`|Describes whether an image has been cropped and, if so, how it was cropped. e.g. 16:9 to 4:3, top and bottom|
|`OriginalSourceForm/Sharpn`|Identifies the changes in sharpness for the digitizer requiered to produce the file|
|`Tagged_Application`|Software used to tag this file|
|`BPM`|Average number of beats per minute|
|`ISRC`|International Standard Recording Code, excluding the ISRC prefix and including hyphens.|
|`ISBN`|International Standard Book Number.|
|`BarCode`|EAN-13 (13-digit European Article Numbering) or UPC-A (12-digit Universal Product Code) bar code identifier.|
|`LCCN`|Library of Congress Control Number.|
|`CatalogNumber`|A label-specific catalogue number used to identify the release. e.g. TIC 01.|
|`LabelCode`|A 4-digit or 5-digit number to identify the record label, typically printed as (LC) xxxx or (LC) 0xxxx on CDs medias or covers, with only the number being stored.|
|`Owner`|Owner of the file|
|`Copyright`|Copyright attribution.|
|`Copyright/Url`|Link to a site with copyright/legal information.|
|`Producer_Copyright`|The copyright information as per the productioncopyright holder.|
|`TermsOfUse`|License information, e.g., All Rights Reserved,Any Use Permitted.|
|`ServiceName`|  |
|`ServiceChannel`|  |
|`Service/Url`|  |
|`ServiceProvider`|  |
|`ServiceProviderr/Url`|  |
|`ServiceType`|  |
|`NetworkName`|  |
|`OriginalNetworkName`|  |
|`Country`|  |
|`TimeZone`|  |
|`Cover`|Is there a cover|
|`Cover_Description`|short descriptio, e.g. Earth in space|
|`Cover_Type`|  |
|`Cover_Mime`|  |
|`Cover_Data`|Cover, in binary format encoded BASE64|
|`Lyrics`|Text of a song|
|`Comment`|Any comment related to the content.|
|`Rating`|A numeric value defining how much a person likes the song/movie. The number is between 0 and 5 with decimal values possible (e.g. 2.7), 5(.0) being the highest possible rating.|
|`Added_Date`|Date/year the item was added to the owners collection|
|`Played_First_Date`|The date, the owner first played an item|
|`Played_Last_Date`|The date, the owner last played an item|
|`Played_Count`|Number of times an item was played|
|`EPG_Positions_Begin`|  |
|`EPG_Positions_End`|  |

## Video ##
| **Property** | **Description** |
|:-------------|:----------------|
|`Count`|Count of objects available in this stream|
|`Status`|bit field (0=IsAccepted, 1=IsFilled, 2=IsUpdated, 3=IsFinished)|
|`StreamCount`|Count of streams of that kind available|
|`StreamKind`|Stream type name|
|`StreamKind/String`|Stream type name|
|`StreamKindID`|Number of the stream (base=0)|
|`StreamKindPos`|When multiple streams, number of the stream (base=1)|
|`StreamOrder`|Stream order in the file, whatever is the kind of stream (base=0)|
|`FirstPacketOrder`|Order of the first fully decodable packet met in the file, whatever is the kind of stream (base=0)|
|`Inform`|Last Inform call|
|`ID`|The ID for this stream in this file|
|`ID/String`|The ID for this stream in this file|
|`UniqueID`|The unique ID for this stream, should be copied with stream copy|
|`UniqueID/String`|The unique ID for this stream, should be copied with stream copy|
|`MenuID`|The menu ID for this stream in this file|
|`MenuID/String`|The menu ID for this stream in this file|
|`Format`|Format used|
|`Format/Info`|Info about Format|
|`Format/Url`|Link|
|`Format_Commercial`|Commercial name used by vendor for theses setings or Format field if there is no difference|
|`Format_Commercial_IfAny`|Commercial name used by vendor for theses setings if there is one|
|`Format_Version`|Version of this format|
|`Format_Profile`|Profile of the Format|
|`Format_Compression`|Compression mode of the Format|
|`MultiView_BaseProfile`|Multiview, profile of the base stream|
|`MultiView_Count`|Multiview, count of views|
|`MultiView_Layout`|Multiview, how views are muxed in the container in case of it is not muxing in the stream|
|`Format_Settings`|Settings needed for decoder used, summary|
|`Format_Settings_BVOP`|Settings needed for decoder used, detailled|
|`Format_Settings_BVOP/Stri`|Settings needed for decoder used, detailled|
|`Format_Settings_QPel`|Settings needed for decoder used, detailled|
|`Format_Settings_QPel/Stri`|Settings needed for decoder used, detailled|
|`Format_Settings_GMC`|Settings needed for decoder used, detailled|
|`Format_Settings_GMC/String` |  |
|`Format_Settings_Matrix`|Settings needed for decoder used, detailled|
|`Format_Settings_Matrix/St`|Settings needed for decoder used, detailled|
|`Format_Settings_Matrix_Da`|Matrix, in binary format encoded BASE64. Order = intra, non-intra, gray intra, gray non-intra|
|`Format_Settings_CABAC`|Settings needed for decoder used, detailled|
|`Format_Settings_CABAC/Str`|Settings needed for decoder used, detailled|
|`Format_Settings_RefFrames`|Settings needed for decoder used, detailled|
|`Format_Settings_RefFrames`|Settings needed for decoder used, detailled|
|`Format_Settings_Pulldown`|Settings needed for decoder used, detailled|
|`Format_Settings_FrameMode`|Settings needed for decoder used, detailled|
|`Format_Settings_GOP`|Settings needed for decoder used, detailled (M=x N=y)|
|`Format_Settings_FrameStru`|Settings needed for decoder used, detailled (Type of frame, and field/frame info)|
|`Format_Settings_Wrapping`|Wrapping mode (Frame wrapped or Clip wrapped)|
|`InternetMediaType`|Internet Media Type (aka MIME Type, Content-Type)|
|`MuxingMode`|How this file is muxed in the container|
|`CodecID`|Codec ID (found in some containers)|
|`CodecID/String`|Codec ID (found in some containers)|
|`CodecID/Info`|Info on the codec|
|`CodecID/Hint`|Hint/popular name for this codec|
|`CodecID/Url`|Homepage for more details about this codec|
|`CodecID_Description`|Manual description given by the container|
|`Codec`|Deprecated, do not use in new projects|
|`Codec/String`|Deprecated, do not use in new projects|
|`Codec/Family`|Deprecated, do not use in new projects|
|`Codec/Info`|Deprecated, do not use in new projects|
|`Codec/Url`|Deprecated, do not use in new projects|
|`Codec/CC`|Deprecated, do not use in new projects|
|`Codec_Profile`|Deprecated, do not use in new projects|
|`Codec_Description`|Deprecated, do not use in new projects|
|`Codec_Settings`|Deprecated, do not use in new projects|
|`Codec_Settings_PacketBitS`|Deprecated, do not use in new projects|
|`Codec_Settings_BVOP`|Deprecated, do not use in new projects|
|`Codec_Settings_QPel`|Deprecated, do not use in new projects|
|`Codec_Settings_GMC`|Deprecated, do not use in new projects|
|`Codec_Settings_GMC/String`|Deprecated, do not use in new projects|
|`Codec_Settings_Matrix`|Deprecated, do not use in new projects|
|`Codec_Settings_Matrix_Dat`|Deprecated, do not use in new projects|
|`Codec_Settings_CABAC`|Deprecated, do not use in new projects|
|`Codec_Settings_RefFrames`|Deprecated, do not use in new projects|
|`Duration`|Play time of the stream in ms|
|`Duration/String`|Play time in format: `XXx YYy` only, YYy omited if zero|
|`Duration/String1`|Play time in format: `HHh MMmn SSs MMMms`, `XX` omited if zero|
|`Duration/String2`|Play time in format: `XXx YYy` only, `YYy` omited if zero|
|`Duration/String3`|Play time in format: `HH:MM:SS.MMM`|
|`Duration/String4`|Play time in format: `HH:MM:SS:FF` (HH:MM:SS|
|`Duration_FirstFrame`|Duration of the first frame if it is longer than others, in ms|
|`Duration_FirstFrame/Strin`|Duration of the first frame if it is longer than others, in format: `XXx YYy` only, YYy omited if zero|
|`Duration_FirstFrame/Strin`|Duration of the first frame if it is longer than others, in format: `HHh MMmn SSs MMMms`, `XX` omited if zero|
|`Duration_FirstFrame/Strin`|Duration of the first frame if it is longer than others, in format: `XXx YYy` only, `YYy` omited if zero|
|`Duration_FirstFrame/Strin`|Duration of the first frame if it is longer than others, in format: `HH:MM:SS.MMM`|
|`Duration_LastFrame`|Duration of the last frame if it is longer than others, in ms|
|`Duration_LastFrame/String`|Duration of the last frame if it is longer than others, in format: `XXx YYy` only, `YYy` omited if zero|
|`Duration_LastFrame/String`|Duration of the last frame if it is longer than others, in format: `HHh MMmn SSs MMMms`, `XX` omited if zero|
|`Duration_LastFrame/String`|Duration of the last frame if it is longer than others, in format: `XXx YYy` only, `YYy` omited if zero|
|`Duration_LastFrame/String`|Duration of the last frame if it is longer than others, in format: `HH:MM:SS.MMM`|
|`Source_Duration`|Source Play time of the stream|
|`Source_Duration/String`|Source Play time in format: `XXx YYy` only, `YYy` omited if zero|
|`Source_Duration/String1`|Source Play time in format: `HHh MMmn SSs MMMms`, `XX` omited if zero|
|`Source_Duration/String2`|Source Play time in format: `XXx YYy` only, `YYy` omited if zero|
|`Source_Duration/String3`|Source Play time in format: `HH:MM:SS.MMM`|
|`Source_Duration_FirstFram`|Source Duration of the first frame if it is longer than others, in ms|
|`Source_Duration_FirstFram`|Source Duration of the first frame if it is longer than others, in format: `XXx YYy` only, `YYy` omited if zero|
|`Source_Duration_FirstFram`|Source Duration of the first frame if it is longer than others, in format: `HHh MMmn SSs MMMms`, `XX` omited if zero|
|`Source_Duration_FirstFram`|Source Duration of the first frame if it is longer than others, in format: `XXx YYy` only, `YYy` omited if zero|
|`Source_Duration_FirstFram`|Source Duration of the first frame if it is longer than others, in format: `HH:MM:SS.MMM`|
|`Source_Duration_LastFrame`|Source Duration of the last frame if it is longer than others, in ms|
|`Source_Duration_LastFrame`|Source Duration of the last frame if it is longer than others, in format: `XXx YYy only`, YYy` omited if zero|
|`Source_Duration_LastFrame`|Source Duration of the last frame if it is longer than others, in format: `HHh MMmn SSs MMMms`, `XX` omited if zero|
|`Source_Duration_LastFrame`|Source Duration of the last frame if it is longer than others, in format: `XXx YYy` only, `YYy` omited if zero|
|`Source_Duration_LastFrame`|Source Duration of the last frame if it is longer than others, in format: `HH:MM:SS.MMM`|
|`BitRate_Mode`|Bit rate mode (VBR, CBR)|
|`BitRate_Mode/String`|Bit rate mode (Variable, Cconstant)|
|`BitRate`|Bit rate in bps|
|`BitRate/String`|Bit rate (with measurement)|
|`BitRate_Minimum`|Minimum Bit rate in bps|
|`BitRate_Minimum/String`|Minimum Bit rate (with measurement)|
|`BitRate_Nominal`|Nominal Bit rate in bps|
|`BitRate_Nominal/String`|Nominal Bit rate (with measurement)|
|`BitRate_Maximum`|Maximum Bit rate in bps|
|`BitRate_Maximum/String`|Maximum Bit rate (with measurement)|
|`BitRate_Encoded`|Encoded (with forced padding) bit rate in bps, if some container padding is present|
|`BitRate_Encoded/String`|Encoded (with forced padding) bit rate (with measurement), if some container padding is present|
|`Width`|Width (aperture size if present) in pixel|
|`Width/String`|Width (aperture size if present) with measurement (pixel)|
|`Width_Offset`|Offset between original width and displayed width (aperture size) in pixel|
|`Width_Offset/String`|Offset between original width and displayed width (aperture size)  in pixel|
|`Width_Original`|Original (in the raw stream) width in pixel|
|`Width_Original/String`|Original (in the raw stream) width with measurement (pixel)|
|`Height`|Height (aperture size if present) in pixel|
|`Height/String`|Height (aperture size if present) with measurement (pixel)|
|`Height_Offset`|Offset between original height and displayed height (aperture size) in pixel|
|`Height_Offset/String`|Offset between original height and displayed height (aperture size)  in pixel|
|`Height_Original`|Original (in the raw stream) height in pixel|
|`Height_Original/String`|Original (in the raw stream) height with measurement (pixel)|
|`PixelAspectRatio`|Pixel Aspect ratio|
|`PixelAspectRatio/String`|Pixel Aspect ratio|
|`PixelAspectRatio_Original`|Original (in the raw stream) Pixel Aspect ratio|
|`PixelAspectRatio_Original`|Original (in the raw stream) Pixel Aspect ratio|
|`DisplayAspectRatio`|Display Aspect ratio|
|`DisplayAspectRatio/String`|Display Aspect ratio|
|`DisplayAspectRatio_Origin`|Original (in the raw stream) Display Aspect ratio|
|`DisplayAspectRatio_Origin`|Original (in the raw stream) Display Aspect ratio|
|`ActiveFormatDescription`|Active Format Description (AFD value)|
|`ActiveFormatDescription/S`|Active Format Description (text)|
|`ActiveFormatDescription_M`|Active Format Description (AFD value) muxing mode (Ancillary or Raw stream)|
|`Rotation`|Rotation|
|`Rotation/String`|Rotation (if not horizontal)|
|`FrameRate_Mode`|Frame rate mode (CFR, VFR)|
|`FrameRate_Mode/String`|Frame rate mode (Constant, Variable)|
|`FrameRate_Mode_Original`|Original frame rate mode (CFR, VFR)|
|`FrameRate_Mode_Original/S`|Original frame rate mode (Constant, Variable)|
|`FrameRate`|Frames per second|
|`FrameRate/String`|Frames per second (with measurement)|
|`FrameRate_Original`|Original (in the raw stream) frames per second|
|`FrameRate_Original/String`|Original (in the raw stream) frames per second (with measurement)|
|`FrameRate_Minimum`|Minimum Frames per second|
|`FrameRate_Minimum/String`|Minimum Frames per second (with measurement)|
|`FrameRate_Nominal`|Nominal Frames per second|
|`FrameRate_Nominal/String`|Nominal Frames per second (with measurement)|
|`FrameRate_Maximum`|Maximum Frames per second|
|`FrameRate_Maximum/String`|Maximum Frames per second (with measurement)|
|`FrameCount`|Number of frames|
|`Source_FrameCount`|Source Number of frames|
|`Standard`|NTSC or PAL|
|`Resolution`|Deprecated, do not use in new projects|
|`Resolution/String`|Deprecated, do not use in new projects|
|`Colorimetry`|Deprecated, do not use in new projects|
|`ColorSpace`|  |
|`ChromaSubsampling`|  |
|`BitDepth`|16/24/32|
|`BitDepth/String`|16/24/32 bits|
|`ScanType`|  |
|`ScanType/String`|  |
|`ScanType_Original`|  |
|`ScanType_Original/String`|  |
|`ScanOrder`|  |
|`ScanOrder/String`|  |
|`ScanOrder_StoredDisplayedInverted`|  |
|`ScanOrder_Original`|  |
|`ScanOrder_Original/String`|  |
|`Interlacement`|Deprecated, do not use in new projects|
|`Interlacement/String`|Deprecated, do not use in new projects|
|`Compression_Mode`|Compression mode (Lossy or Lossless)|
|`Compression_Mode/String`|Compression mode (Lossy or Lossless)|
|`Compression_Ratio`|Current stream size divided by uncompressed stream size|
|`Bits-(Pixel*Frame)`|bits/(Pixel\*Frame) (like Gordian Knot)|
|`Delay`|Delay fixed in the stream (relative) IN MS|
|`Delay/String`|Delay with measurement|
|`Delay/String1`|Delay with measurement|
|`Delay/String2`|Delay with measurement|
|`Delay/String3`|Delay in format: `HH:MM:SS.MMM`|
|`Delay/String4`|Delay in format: `HH:MM:SS:FF (HH:MM:SS`|
|`Delay_Settings`|Delay settings (in case of timecode for example)|
|`Delay_DropFrame`|Delay drop frame|
|`Delay_Source`|Delay source (Container or Stream or empty)|
|`Delay_Source/String`|Delay source (Container or Stream or empty)|
|`Delay_Original`|Delay fixed in the raw stream (relative) IN MS|
|`Delay_Original/String`|Delay with measurement|
|`Delay_Original/String1`|Delay with measurement|
|`Delay_Original/String2`|Delay with measurement|
|`Delay_Original/String3`|Delay in format: `HH:MM:SS.MMM`|
|`Delay_Original/String4`|Delay in format: `HH:MM:SS:FF (HH:MM:SS`|
|`Delay_Original_Settings`|Delay settings (in case of timecode for example)|
|`Delay_Original_DropFrame`|Delay drop frame info|
|`Delay_Original_Source`|Delay source (Stream or empty)|
|`TimeStamp_FirstFrame`|TimeStamp fixed in the stream (relative) IN MS|
|`TimeStamp_FirstFrame/Stri`|TimeStamp with measurement|
|`TimeStamp_FirstFrame/Stri`|TimeStamp with measurement|
|`TimeStamp_FirstFrame/Stri`|TimeStamp with measurement|
|`TimeStamp_FirstFrame/Stri`|TimeStamp in format: `HH:MM:SS.MMM`|
|`TimeCode_FirstFrame`|Time code in `HH:MM:SS:FF` (HH:MM:SS`|
|`TimeCode_Settings`|Time code settings|
|`TimeCode_Source`|Time code source (Container, Stream, SystemScheme1, SDTI, ANC...)|
|`StreamSize`|Streamsize in bytes|
|`StreamSize/String`|Streamsize in with percentage value|
|`StreamSize/String1`|  |
|`StreamSize/String2`|  |
|`StreamSize/String3`|  |
|`StreamSize/String4`|  |
|`StreamSize/String5`|Streamsize in with percentage value|
|`StreamSize_Proportion`|Stream size divided by file size|
|`Source_StreamSize`|Source Streamsize in bytes|
|`Source_StreamSize/String`|Source Streamsize in with percentage value|
|`Source_StreamSize/String1`|  |
|`Source_StreamSize/String2`|  |
|`Source_StreamSize/String3`|  |
|`Source_StreamSize/String4`|  |
|`Source_StreamSize/String5`|Source Streamsize in with percentage value|
|`Source_StreamSize_Proport`|Source Stream size divided by file size|
|`StreamSize_Encoded`|Encoded Streamsize in bytes|
|`StreamSize_Encoded/String`|Encoded Streamsize in with percentage value|
|`StreamSize_Encoded/String1`|  |
|`StreamSize_Encoded/String2`|  |
|`StreamSize_Encoded/String3`|  |
|`StreamSize_Encoded/String4`|  |
|`StreamSize_Encoded/String`|Encoded Streamsize in with percentage value|
|`StreamSize_Encoded_Propor`|Encoded Stream size divided by file size|
|`Source_StreamSize_Encoded`|Source Encoded Streamsize in bytes|
|`Source_StreamSize_Encoded`|Source Encoded Streamsize in with percentage value|
|`Source_StreamSize_Encoded/String1`|  |
|`Source_StreamSize_Encoded/String2`|  |
|`Source_StreamSize_Encoded/String3`|  |
|`Source_StreamSize_Encoded/String4`|  |
|`Source_StreamSize_Encoded`|Source Encoded Streamsize in with percentage value|
|`Source_StreamSize_Encoded`|Source Encoded Stream size divided by file size|
|`Alignment`|How this stream file is aligned in the container|
|`Alignment/String`|  |
|`Title`|Name of the track|
|`Encoded_Application`|Software. Identifies the name of the software package used to create the file, such as Microsoft WaveEdit.|
|`Encoded_Application/Url`|Software. Identifies the name of the software package used to create the file, such as Microsoft WaveEdit.|
|`Encoded_Library`|Software used to create the file|
|`Encoded_Library/String`|Software used to create the file|
|`Encoded_Library/Name`|Info from the software|
|`Encoded_Library/Version`|Version of software|
|`Encoded_Library/Date`|Release date of software|
|`Encoded_Library_Settings`|Parameters used by the software|
|`Language`|Language (2-letter ISO 639-1 if exists, else 3-letter ISO 639-2, and with optional ISO 3166-1 country separated by a dash if available, e.g. en, en-us, zh-cn)|
|`Language/String`|Language (full)|
|`Language/String1`|Language (full)|
|`Language/String2`|Language (2-letter ISO 639-1 if exists, else empty)|
|`Language/String3`|Language (3-letter ISO 639-2 if exists, else empty)|
|`Language/String4`|Language (2-letter ISO 639-1 if exists with optional ISO 3166-1 country separated by a dash if available, e.g. en, en-us, zh-cn, else empty)|
|`Language_More`|More info about Language (e.g. Director's Comment)|
|`Default`|Set if that track should be used if no language found matches the user preference.|
|`Default/String`|Set if that track should be used if no language found matches the user preference.|
|`Forced`|Set if that track should be used if no language found matches the user preference.|
|`Forced/String`|Set if that track should be used if no language found matches the user preference.|
|`Encoded_Date`|UTC time that the encoding of this item was completed began.|
|`Tagged_Date`|UTC time that the tags were done for this item.|
|`Encryption`|  |
|`BufferSize`|Defines the size of the buffer needed to decode the sequence.|
|`colour_description_presen`|Presence of colour description|
|`colour_primaries`|Chromaticity coordinates of the source primaries|
|`transfer_characteristics`|Opto-electronic transfer characteristic of the source picture|
|`matrix_coefficients`|Matrix coefficients used in deriving luma and chroma signals from the green, blue, and red primaries|
|`colour_description_presen`|Presence of colour description|
|`colour_primaries_Original`|Chromaticity coordinates of the source primaries|
|`transfer_characteristics_`|Opto-electronic transfer characteristic of the source picture|
|`matrix_coefficients_Origi`|Matrix coefficients used in deriving luma and chroma signals from the green, blue, and red primaries|

## Audio ##
| **Property** | **Description** |
|:-------------|:----------------|
|`Count`|Count of objects available in this stream|
|`Status`|bit field (0=IsAccepted, 1=IsFilled, 2=IsUpdated, 3=IsFinished)|
|`StreamCount`|Count of streams of that kind available|
|`StreamKind`|Stream type name|
|`StreamKind/String`|Stream type name|
|`StreamKindID`|Number of the stream (base=0)|
|`StreamKindPos`|When multiple streams, number of the stream (base=1)|
|`StreamOrder`|Stream order in the file, whatever is the kind of stream (base=0)|
|`FirstPacketOrder`|Order of the first fully decodable packet met in the file, whatever is the kind of stream (base=0)|
|`Inform`|Last Inform call|
|`ID`|The ID for this stream in this file|
|`ID/String`|The ID for this stream in this file|
|`UniqueID`|The unique ID for this stream, should be copied with stream copy|
|`UniqueID/String`|The unique ID for this stream, should be copied with stream copy|
|`MenuID`|The menu ID for this stream in this file|
|`MenuID/String`|The menu ID for this stream in this file|
|`Format`|Format used|
|`Format/Info`|Info about the format|
|`Format/Url`|Homepage of this format|
|`Format_Commercial`|Commercial name used by vendor for theses setings or Format field if there is no difference|
|`Format_Commercial_IfAny`|Commercial name used by vendor for theses setings if there is one|
|`Format_Version`|Version of this format|
|`Format_Profile`|Profile of this Format|
|`Format_Compression`|Compression method used|
|`Format_Settings`|Settings needed for decoder used, summary|
|`Format_Settings_SBR` |  |
|`Format_Settings_SBR/String` |  |
|`Format_Settings_PS` |  |
|`Format_Settings_PS/String` |  |
|`Format_Settings_Mode` |  |
|`Format_Settings_ModeExtension` |  |
|`Format_Settings_Emphasis` |  |
|`Format_Settings_Floor` |  |
|`Format_Settings_Firm` |  |
|`Format_Settings_Endianness` |  |
|`Format_Settings_Sign` |  |
|`Format_Settings_Law` |  |
|`Format_Settings_ITU` |  |
|`Format_Settings_Wrapping`|Wrapping mode (Frame wrapped or Clip wrapped)|
|`InternetMediaType`|Internet Media Type (aka MIME Type, Content-Type)|
|`MuxingMode`|How this stream is muxed in the container|
|`MuxingMode_MoreInfo`|More info (text) about the muxing mode|
|`CodecID`|Codec ID (found in some containers)|
|`CodecID/String`|Codec ID (found in some containers)|
|`CodecID/Info`|Info about codec ID|
|`CodecID/Hint`|Hint/popular name for this codec ID|
|`CodecID/Url`|Homepage for more details about this codec ID|
|`CodecID_Description`|Manual description given by the container|
|`Codec`|Deprecated, do not use in new projects|
|`Codec/String`|Deprecated, do not use in new projects|
|`Codec/Family`|Deprecated, do not use in new projects|
|`Codec/Info`|Deprecated, do not use in new projects|
|`Codec/Url`|Deprecated, do not use in new projects|
|`Codec/CC`|Deprecated, do not use in new projects|
|`Codec_Description`|Deprecated, do not use in new projects|
|`Codec_Profile`|Deprecated, do not use in new projects|
|`Codec_Settings`|Deprecated, do not use in new projects|
|`Codec_Settings_Automatic`|Deprecated, do not use in new projects|
|`Codec_Settings_Floor`|Deprecated, do not use in new projects|
|`Codec_Settings_Firm`|Deprecated, do not use in new projects|
|`Codec_Settings_Endianness`|Deprecated, do not use in new projects|
|`Codec_Settings_Sign`|Deprecated, do not use in new projects|
|`Codec_Settings_Law`|Deprecated, do not use in new projects|
|`Codec_Settings_ITU`|Deprecated, do not use in new projects|
|`Duration`|Play time of the stream|
|`Duration/String`|Play time in format: XXx YYy only, YYy omited if zero|
|`Duration/String1`|Play time in format: HHh MMmn SSs MMMms, XX omited if zero|
|`Duration/String2`|Play time in format: XXx YYy only, YYy omited if zero|
|`Duration/String3`|Play time in format: HH:MM:SS.MMM|
|`Duration_FirstFrame`|Duration of the first frame if it is longer than others, in ms|
|`Duration_FirstFrame/Strin`|Duration of the first frame if it is longer than others, in format: XXx YYy only, YYy omited if zero|
|`Duration_FirstFrame/Strin`|Duration of the first frame if it is longer than others, in format: HHh MMmn SSs MMMms, XX omited if zero|
|`Duration_FirstFrame/Strin`|Duration of the first frame if it is longer than others, in format: XXx YYy only, YYy omited if zero|
|`Duration_FirstFrame/Strin`|Duration of the first frame if it is longer than others, in format: HH:MM:SS.MMM|
|`Duration_LastFrame`|Duration of the last frame if it is longer than others, in ms|
|`Duration_LastFrame/String`|Duration of the last frame if it is longer than others, in format: XXx YYy only, YYy omited if zero|
|`Duration_LastFrame/String`|Duration of the last frame if it is longer than others, in format: HHh MMmn SSs MMMms, XX omited if zero|
|`Duration_LastFrame/String`|Duration of the last frame if it is longer than others, in format: XXx YYy only, YYy omited if zero|
|`Duration_LastFrame/String`|Duration of the last frame if it is longer than others, in format: HH:MM:SS.MMM|
|`Source_Duration`|Source Play time of the stream|
|`Source_Duration/String`|Source Play time in format: XXx YYy only, YYy omited if zero|
|`Source_Duration/String1`|Source Play time in format: HHh MMmn SSs MMMms, XX omited if zero|
|`Source_Duration/String2`|Source Play time in format: XXx YYy only, YYy omited if zero|
|`Source_Duration/String3`|Source Play time in format: HH:MM:SS.MMM|
|`Source_Duration_FirstFram`|Source Duration of the first frame if it is longer than others, in ms|
|`Source_Duration_FirstFram`|Source Duration of the first frame if it is longer than others, in format: XXx YYy only, YYy omited if zero|
|`Source_Duration_FirstFram`|Source Duration of the first frame if it is longer than others, in format: HHh MMmn SSs MMMms, XX omited if zero|
|`Source_Duration_FirstFram`|Source Duration of the first frame if it is longer than others, in format: XXx YYy only, YYy omited if zero|
|`Source_Duration_FirstFram`|Source Duration of the first frame if it is longer than others, in format: HH:MM:SS.MMM|
|`Source_Duration_LastFrame`|Source Duration of the last frame if it is longer than others, in ms|
|`Source_Duration_LastFrame`|Source Duration of the last frame if it is longer than others, in format: XXx YYy only, YYy omited if zero|
|`Source_Duration_LastFrame`|Source Duration of the last frame if it is longer than others, in format: HHh MMmn SSs MMMms, XX omited if zero|
|`Source_Duration_LastFrame`|Source Duration of the last frame if it is longer than others, in format: XXx YYy only, YYy omited if zero|
|`Source_Duration_LastFrame`|Source Duration of the last frame if it is longer than others, in format: HH:MM:SS.MMM|
|`BitRate_Mode`|Bit rate mode (VBR, CBR)|
|`BitRate_Mode/String`|Bit rate mode (Constant, Variable)|
|`BitRate`|Bit rate in bps|
|`BitRate/String`|Bit rate (with measurement)|
|`BitRate_Minimum`|Minimum Bit rate in bps|
|`BitRate_Minimum/String`|Minimum Bit rate (with measurement)|
|`BitRate_Nominal`|Nominal Bit rate in bps|
|`BitRate_Nominal/String`|Nominal Bit rate (with measurement)|
|`BitRate_Maximum`|Maximum Bit rate in bps|
|`BitRate_Maximum/String`|Maximum Bit rate (with measurement)|
|`BitRate_Encoded`|Encoded (with forced padding) bit rate in bps, if some container padding is present|
|`BitRate_Encoded/String`|Encoded (with forced padding) bit rate (with measurement), if some container padding is present|
|`Channel(s)`|Number of channels|
|`Channel(s)/String`|Number of channels (with measurement)|
|`Channel(s)_Original`|Number of channels|
|`Channel(s)_Original/Strin`|Number of channels (with measurement)|
|`ChannelPositions`|Position of channels|
|`ChannelPositions/String2`|Position of channels (x/y.z format)|
|`ChannelLayout`|Layout of channels (in the stream)|
|`SamplingRate`|Sampling rate|
|`SamplingRate/String`|in KHz|
|`SamplingCount`|Sample count (based on sampling rate)|
|`Source_SamplingCount`|Source Sample count (based on sampling rate)|
|`FrameRate`|Frames per second|
|`FrameRate/String`|Frames per second (with measurement)|
|`FrameCount`|Frame count (a frame contains a count of samples depends of the format)|
|`Source_FrameCount`|Source Frame count (a frame contains a count of samples depends of the format)|
|`Resolution`|Deprecated, do not use in new projects|
|`Resolution/String`|Deprecated, do not use in new projects|
|`BitDepth`|Resolution in bits (8, 16, 20, 24)|
|`BitDepth/String`|Resolution in bits (8, 16, 20, 24)|
|`Compression_Mode`|Compression mode (Lossy or Lossless)|
|`Compression_Mode/String`|Compression mode (Lossy or Lossless)|
|`Compression_Ratio`|Current stream size divided by uncompressed stream size|
|`Delay`|Delay fixed in the stream (relative) IN MS|
|`Delay/String`|Delay with measurement|
|`Delay/String1`|Delay with measurement|
|`Delay/String2`|Delay with measurement|
|`Delay/String3`|Delay in format: HH:MM:SS.MMM|
|`Delay/String4`|Delay in format: HH:MM:SS:FF (HH:MM:SS|
|`Delay_Settings`|Delay settings (in case of timecode for example)|
|`Delay_DropFrame`|Delay drop frame|
|`Delay_Source`|Delay source (Container or Stream or empty)|
|`Delay_Source/String`|Delay source (Container or Stream or empty)|
|`Delay_Original`|Delay fixed in the raw stream (relative) IN MS|
|`Delay_Original/String`|Delay with measurement|
|`Delay_Original/String1`|Delay with measurement|
|`Delay_Original/String2`|Delay with measurement|
|`Delay_Original/String3`|Delay in format: HH:MM:SS.MMM|
|`Delay_Original/String4`|Delay in format: HH:MM:SS:FF (HH:MM:SS|
|`Delay_Original_Settings`|Delay settings (in case of timecode for example)|
|`Delay_Original_DropFrame`|Delay drop frame info|
|`Delay_Original_Source`|Delay source (Stream or empty)|
|`Video_Delay`|Delay fixed in the stream (absolute / video)|
|`Video_Delay/String`|  |
|`Video_Delay/String1`|  |
|`Video_Delay/String2`|  |
|`Video_Delay/String3`|  |
|`Video_Delay/String4`|  |
|`Video0_Delay`|Deprecated, do not use in new projects|
|`Video0_Delay/String`|Deprecated, do not use in new projects|
|`Video0_Delay/String1`|Deprecated, do not use in new projects|
|`Video0_Delay/String2`|Deprecated, do not use in new projects|
|`Video0_Delay/String3`|Deprecated, do not use in new projects|
|`Video0_Delay/String4`|Deprecated, do not use in new projects|
|`ReplayGain_Gain`|The gain to apply to reach 89dB SPL on playback|
|`ReplayGain_Gain/String`|  |
|`ReplayGain_Peak`|The maximum absolute peak value of the item|
|`StreamSize`|Streamsize in bytes|
|`StreamSize/String`|Streamsize in with percentage value|
|`StreamSize/String1`|  |
|`StreamSize/String2`|  |
|`StreamSize/String3`|  |
|`StreamSize/String4`|  |
|`StreamSize/String5`|Streamsize in with percentage value|
|`StreamSize_Proportion`|Stream size divided by file size|
|`Source_StreamSize`|Source Streamsize in bytes|
|`Source_StreamSize/String`|Source Streamsize in with percentage value|
|`Source_StreamSize/String1`|  |
|`Source_StreamSize/String2`|  |
|`Source_StreamSize/String3`|  |
|`Source_StreamSize/String4`|  |
|`Source_StreamSize/String5`|Source Streamsize in with percentage value|
|`Source_StreamSize_Proport`|Source Stream size divided by file size|
|`StreamSize_Encoded`|Encoded Streamsize in bytes|
|`StreamSize_Encoded/String`|Encoded Streamsize in with percentage value|
|`StreamSize_Encoded/String1`|  |
|`StreamSize_Encoded/String2`|  |
|`StreamSize_Encoded/String3`|  |
|`StreamSize_Encoded/String4`|  |
|`StreamSize_Encoded/String`|Encoded Streamsize in with percentage value|
|`StreamSize_Encoded_Propor`|Encoded Stream size divided by file size|
|`Source_StreamSize_Encoded`|Source Encoded Streamsize in bytes|
|`Source_StreamSize_Encoded`|Source Encoded Streamsize in with percentage value|
|`Source_StreamSize_Encoded/String1`|  |
|`Source_StreamSize_Encoded/String2`|  |
|`Source_StreamSize_Encoded/String3`|  |
|`Source_StreamSize_Encoded/String4`|  |
|`Source_StreamSize_Encoded`|Source Encoded Streamsize in with percentage value|
|`Source_StreamSize_Encoded`|Source Encoded Stream size divided by file size|
|`Alignment`|How this stream file is aligned in the container|
|`Alignment/String`|Where this stream file is aligned in the container|
|`Interleave_VideoFrames`|Between how many video frames the stream is inserted|
|`Interleave_Duration`|Between how much time (ms) the stream is inserted|
|`Interleave_Duration/Strin`|Between how much time and video frames the stream is inserted (with measurement)|
|`Interleave_Preload`|How much time is buffered before the first video frame|
|`Interleave_Preload/String`|How much time is buffered before the first video frame (with measurement)|
|`Title`|Name of the track|
|`Encoded_Library`|Software used to create the file|
|`Encoded_Library/String`|Software used to create the file|
|`Encoded_Library/Name`|Info from the software|
|`Encoded_Library/Version`|Version of software|
|`Encoded_Library/Date`|Release date of software|
|`Encoded_Library_Settings`|Parameters used by the software|
|`Language`|Language (2-letter ISO 639-1 if exists, else 3-letter ISO 639-2, and with optional ISO 3166-1 country separated by a dash if available, e.g. en, en-us, zh-cn)|
|`Language/String`|Language (full)|
|`Language/String1`|Language (full)|
|`Language/String2`|Language (2-letter ISO 639-1 if exists, else empty)|
|`Language/String3`|Language (3-letter ISO 639-2 if exists, else empty)|
|`Language/String4`|Language (2-letter ISO 639-1 if exists with optional ISO 3166-1 country separated by a dash if available, e.g. en, en-us, zh-cn, else empty)|
|`Language_More`|More info about Language (e.g. Director's Comment)|
|`Default`|Set if that track should be used if no language found matches the user preference.|
|`Default/String`|Set if that track should be used if no language found matches the user preference.|
|`Forced`|Set if that track should be used if no language found matches the user preference.|
|`Forced/String`|Set if that track should be used if no language found matches the user preference.|
|`Encoded_Date`|UTC time that the encoding of this item was completed began.|
|`Tagged_Date`|UTC time that the tags were done for this item.|
|`Encryption`|  |

## Text ##
| **Property** | **Description** |
|:-------------|:----------------|
|`Count`|Count of objects available in this stream|
|`Status`|bit field (0=IsAccepted, 1=IsFilled, 2=IsUpdated, 3=IsFinished)|
|`StreamCount`|Count of streams of that kind available|
|`StreamKind`|Stream type name|
|`StreamKind/String`|Stream type name|
|`StreamKindID`|Number of the stream (base=0)|
|`StreamKindPos`|When multiple streams, number of the stream (base=1)|
|`StreamOrder`|Stream order in the file, whatever is the kind of stream (base=0)|
|`FirstPacketOrder`|Order of the first fully decodable packet met in the file, whatever is the kind of stream (base=0)|
|`Inform`|Last Inform call|
|`ID`|The ID for this stream in this file|
|`ID/String`|The ID for this stream in this file|
|`UniqueID`|The unique ID for this stream, should be copied with stream copy|
|`UniqueID/String`|The unique ID for this stream, should be copied with stream copy|
|`MenuID`|The menu ID for this stream in this file|
|`MenuID/String`|The menu ID for this stream in this file|
|`Format`|Format used|
|`Format/Info`|Info about Format|
|`Format/Url`|Link|
|`Format_Commercial`|Commercial name used by vendor for theses setings or Format field if there is no difference|
|`Format_Commercial_IfAny`|Commercial name used by vendor for theses setings if there is one|
|`Format_Version`|Version of this format|
|`Format_Profile`|Profile of the Format|
|`Format_Compression`|Compression method used|
|`Format_Settings`|Settings needed for decoder used|
|`Format_Settings_Wrapping`|Wrapping mode (Frame wrapped or Clip wrapped)|
|`InternetMediaType`|Internet Media Type (aka MIME Type, Content-Type)|
|`MuxingMode`|How this stream is muxed in the container|
|`MuxingMode_MoreInfo`|More info (text) about the muxing mode|
|`CodecID`|Codec ID (found in some containers)|
|`CodecID/String`|Codec ID (found in some containers)|
|`CodecID/Info`|Info about codec ID|
|`CodecID/Hint`|A hint for this codec ID|
|`CodecID/Url`|A link for more details about this codec ID|
|`CodecID_Description`|Manual description given by the container|
|`Codec`|Deprecated|
|`Codec/String`|Deprecated|
|`Codec/Info`|Deprecated|
|`Codec/Url`|Deprecated|
|`Codec/CC`|Deprecated|
|`Duration`|Play time of the stream|
|`Duration/String`|Play time (formated)|
|`Duration/String1`|Play time in format: HHh MMmn SSs MMMms, XX omited if zero|
|`Duration/String2`|Play time in format: XXx YYy only, YYy omited if zero|
|`Duration/String3`|Play time in format: HH:MM:SS.MMM|
|`Duration/String4`|Play time in format: HH:MM:SS:FF (HH:MM:SS|
|`Duration_FirstFrame`|Duration of the first frame if it is longer than others, in ms|
|`Duration_FirstFrame/Strin`|Duration of the first frame if it is longer than others, in format: XXx YYy only, YYy omited if zero|
|`Duration_FirstFrame/Strin`|Duration of the first frame if it is longer than others, in format: HHh MMmn SSs MMMms, XX omited if zero|
|`Duration_FirstFrame/Strin`|Duration of the first frame if it is longer than others, in format: XXx YYy only, YYy omited if zero|
|`Duration_FirstFrame/Strin`|Duration of the first frame if it is longer than others, in format: HH:MM:SS.MMM|
|`Duration_LastFrame`|Duration of the last frame if it is longer than others, in ms|
|`Duration_LastFrame/String`|Duration of the last frame if it is longer than others, in format: XXx YYy only, YYy omited if zero|
|`Duration_LastFrame/String`|Duration of the last frame if it is longer than others, in format: HHh MMmn SSs MMMms, XX omited if zero|
|`Duration_LastFrame/String`|Duration of the last frame if it is longer than others, in format: XXx YYy only, YYy omited if zero|
|`Duration_LastFrame/String`|Duration of the last frame if it is longer than others, in format: HH:MM:SS.MMM|
|`Source_Duration`|Source Play time of the stream|
|`Source_Duration/String`|Source Play time in format: XXx YYy only, YYy omited if zero|
|`Source_Duration/String1`|Source Play time in format: HHh MMmn SSs MMMms, XX omited if zero|
|`Source_Duration/String2`|Source Play time in format: XXx YYy only, YYy omited if zero|
|`Source_Duration/String3`|Source Play time in format: HH:MM:SS.MMM|
|`Source_Duration_FirstFram`|Source Duration of the first frame if it is longer than others, in ms|
|`Source_Duration_FirstFram`|Source Duration of the first frame if it is longer than others, in format: XXx YYy only, YYy omited if zero|
|`Source_Duration_FirstFram`|Source Duration of the first frame if it is longer than others, in format: HHh MMmn SSs MMMms, XX omited if zero|
|`Source_Duration_FirstFram`|Source Duration of the first frame if it is longer than others, in format: XXx YYy only, YYy omited if zero|
|`Source_Duration_FirstFram`|Source Duration of the first frame if it is longer than others, in format: HH:MM:SS.MMM|
|`Source_Duration_LastFrame`|Source Duration of the last frame if it is longer than others, in ms|
|`Source_Duration_LastFrame`|Source Duration of the last frame if it is longer than others, in format: XXx YYy only, YYy omited if zero|
|`Source_Duration_LastFrame`|Source Duration of the last frame if it is longer than others, in format: HHh MMmn SSs MMMms, XX omited if zero|
|`Source_Duration_LastFrame`|Source Duration of the last frame if it is longer than others, in format: XXx YYy only, YYy omited if zero|
|`Source_Duration_LastFrame`|Source Duration of the last frame if it is longer than others, in format: HH:MM:SS.MMM|
|`BitRate_Mode`|Bit rate mode (VBR, CBR)|
|`BitRate_Mode/String`|Bit rate mode (Constant, Variable)|
|`BitRate`|Bit rate in bps|
|`BitRate/String`|Bit rate (with measurement)|
|`BitRate_Minimum`|Minimum Bit rate in bps|
|`BitRate_Minimum/String`|Minimum Bit rate (with measurement)|
|`BitRate_Nominal`|Nominal Bit rate in bps|
|`BitRate_Nominal/String`|Nominal Bit rate (with measurement)|
|`BitRate_Maximum`|Maximum Bit rate in bps|
|`BitRate_Maximum/String`|Maximum Bit rate (with measurement)|
|`BitRate_Encoded`|Encoded (with forced padding) bit rate in bps, if some container padding is present|
|`BitRate_Encoded/String`|Encoded (with forced padding) bit rate (with measurement), if some container padding is present|
|`Width`|Width|
|`Width/String`|  |
|`Height`|Height|
|`Height/String`|  |
|`FrameRate_Mode`|Frame rate mode (CFR, VFR)|
|`FrameRate_Mode/String`|Frame rate mode (Constant, Variable)|
|`FrameRate`|Frames per second|
|`FrameRate/String`|Frames per second (with measurement)|
|`FrameRate_Minimum`|Minimum Frames per second|
|`FrameRate_Minimum/String`|Minimum Frames per second (with measurement)|
|`FrameRate_Nominal`|Nominal Frames per second|
|`FrameRate_Nominal/String`|Nominal Frames per second (with measurement)|
|`FrameRate_Maximum`|Maximum Frames per second|
|`FrameRate_Maximum/String`|Maximum Frames per second (with measurement)|
|`FrameRate_Original`|Original (in the raw stream) Frames per second|
|`FrameRate_Original/String`|Original (in the raw stream) Frames per second (with measurement)|
|`FrameCount`|Number of frames|
|`Source_FrameCount`|Source Number of frames|
|`ColorSpace`|  |
|`ChromaSubsampling`|  |
|`Resolution`|Deprecated, do not use in new projects|
|`Resolution/String`|Deprecated, do not use in new projects|
|`BitDepth`|  |
|`BitDepth/String`|  |
|`Compression_Mode`|Compression mode (Lossy or Lossless)|
|`Compression_Mode/String`|Compression mode (Lossy or Lossless)|
|`Compression_Ratio`|Current stream size divided by uncompressed stream size|
|`Delay`|Delay fixed in the stream (relative) IN MS|
|`Delay/String`|Delay with measurement|
|`Delay/String1`|Delay with measurement|
|`Delay/String2`|Delay with measurement|
|`Delay/String3`|Delay in format: HH:MM:SS.MMM|
|`Delay/String4`|Delay in format: HH:MM:SS:FF (HH:MM:SS|
|`Delay_Settings`|Delay settings (in case of timecode for example)|
|`Delay_DropFrame`|Delay drop frame|
|`Delay_Source`|Delay source (Container or Stream or empty)|
|`Delay_Source/String`|Delay source (Container or Stream or empty)|
|`Delay_Original`|Delay fixed in the raw stream (relative) IN MS|
|`Delay_Original/String`|Delay with measurement|
|`Delay_Original/String1`|Delay with measurement|
|`Delay_Original/String2`|Delay with measurement|
|`Delay_Original/String3`|Delay in format: HH:MM:SS.MMM|
|`Delay_Original/String4`|Delay in format: HH:MM:SS:FF (HH:MM:SS|
|`Delay_Original_Settings`|Delay settings (in case of timecode for example)|
|`Delay_Original_DropFrame`|Delay drop frame info|
|`Delay_Original_Source`|Delay source (Stream or empty)|
|`Video_Delay`|Delay fixed in the stream (absolute / video)|
|`Video_Delay/String`|  |
|`Video_Delay/String1`|  |
|`Video_Delay/String2`|  |
|`Video_Delay/String3`|  |
|`Video_Delay/String4`|  |
|`Video0_Delay`|Deprecated, do not use in new projects|
|`Video0_Delay/String`|Deprecated, do not use in new projects|
|`Video0_Delay/String1`|Deprecated, do not use in new projects|
|`Video0_Delay/String2`|Deprecated, do not use in new projects|
|`Video0_Delay/String3`|Deprecated, do not use in new projects|
|`Video0_Delay/String4`|Deprecated, do not use in new projects|
|`StreamSize`|Streamsize in bytes|
|`StreamSize/String`|Streamsize in with percentage value|
|`StreamSize/String1`|  |
|`StreamSize/String2`|  |
|`StreamSize/String3`|  |
|`StreamSize/String4`|  |
|`StreamSize/String5`|Streamsize in with percentage value|
|`StreamSize_Proportion`|Stream size divided by file size|
|`Source_StreamSize`|Source Streamsize in bytes|
|`Source_StreamSize/String`|Source Streamsize in with percentage value|
|`Source_StreamSize/String1`|  |
|`Source_StreamSize/String2`|  |
|`Source_StreamSize/String3`|  |
|`Source_StreamSize/String4`|  |
|`Source_StreamSize/String5`|Source Streamsize in with percentage value|
|`Source_StreamSize_Proport`|Source Stream size divided by file size|
|`StreamSize_Encoded`|Encoded Streamsize in bytes|
|`StreamSize_Encoded/String`|Encoded Streamsize in with percentage value|
|`StreamSize_Encoded/String1`|  |
|`StreamSize_Encoded/String2`|  |
|`StreamSize_Encoded/String3`|  |
|`StreamSize_Encoded/String4`|  |
|`StreamSize_Encoded/String`|Encoded Streamsize in with percentage value|
|`StreamSize_Encoded_Propor`|Encoded Stream size divided by file size|
|`Source_StreamSize_Encoded`|Source Encoded Streamsize in bytes|
|`Source_StreamSize_Encoded`|Source Encoded Streamsize in with percentage value|
|`Source_StreamSize_Encoded/String1`|  |
|`Source_StreamSize_Encoded/String2`|  |
|`Source_StreamSize_Encoded/String3`|  |
|`Source_StreamSize_Encoded/String4`|  |
|`Source_StreamSize_Encoded`|Source Encoded Streamsize in with percentage value|
|`Source_StreamSize_Encoded`|Source Encoded Stream size divided by file size|
|`Title`|Name of the track|
|`Encoded_Library`|Software used to create the file|
|`Encoded_Library/String`|Software used to create the file|
|`Encoded_Library/Name`|Info from the software|
|`Encoded_Library/Version`|Version of software|
|`Encoded_Library/Date`|Release date of software|
|`Encoded_Library_Settings`|Parameters used by the software|
|`Language`|Language (2-letter ISO 639-1 if exists, else 3-letter ISO 639-2, and with optional ISO 3166-1 country separated by a dash if available, e.g. en, en-us, zh-cn)|
|`Language/String`|Language (full)|
|`Language/String1`|Language (full)|
|`Language/String2`|Language (2-letter ISO 639-1 if exists, else empty)|
|`Language/String3`|Language (3-letter ISO 639-2 if exists, else empty)|
|`Language/String4`|Language (2-letter ISO 639-1 if exists with optional ISO 3166-1 country separated by a dash if available, e.g. en, en-us, zh-cn, else empty)|
|`Language_More`|More info about Language (e.g. Director's Comment)|
|`Default`|Set if that track should be used if no language found matches the user preference.|
|`Default/String`|Set if that track should be used if no language found matches the user preference.|
|`Forced`|Set if that track should be used if no language found matches the user preference.|
|`Forced/String`|Set if that track should be used if no language found matches the user preference.|
|`Summary`|  |
|`Encoded_Date`|The time that the encoding of this item was completed began.|
|`Tagged_Date`|The time that the tags were done for this item.|
|`Encryption`|  |

## Other ##
| **Property** | **Description** |
|:-------------|:----------------|
|`Count`|Count of objects available in this stream|
|`Status`|bit field (0=IsAccepted, 1=IsFilled, 2=IsUpdated, 3=IsFinished)|
|`StreamCount`|Count of streams of that kind available|
|`StreamKind`|Stream type name|
|`StreamKind/String`|Stream type name|
|`StreamKindID`|Number of the stream (base=0)|
|`StreamKindPos`|When multiple streams, number of the stream (base=1)|
|`StreamOrder`|Stream order in the file, whatever is the kind of stream (base=0)|
|`FirstPacketOrder`|Order of the first fully decodable packet met in the file, whatever is the kind of stream (base=0)|
|`Inform`|Last Inform call|
|`ID`|The ID for this stream in this file|
|`ID/String`|The ID for this stream in this file|
|`UniqueID`|The unique ID for this stream, should be copied with stream copy|
|`UniqueID/String`|The unique ID for this stream, should be copied with stream copy|
|`MenuID`|The menu ID for this stream in this file|
|`MenuID/String`|The menu ID for this stream in this file|
|`Type`|Type|
|`Format`|Format used|
|`Format/Info`|Info about Format|
|`Format/Url`|Link|
|`Format_Commercial`|Commercial name used by vendor for theses setings or Format field if there is no difference|
|`Format_Commercial_IfAny`|Commercial name used by vendor for theses setings if there is one|
|`Format_Version`|Version of this format|
|`Format_Profile`|Profile of the Format|
|`Format_Compression`|Compression method used|
|`Format_Settings`|Settings needed for decoder used|
|`MuxingMode`|How this file is muxed in the container|
|`CodecID`|Codec ID (found in some containers)|
|`CodecID/String`|Codec ID (found in some containers)|
|`CodecID/Info`|Info about this codec|
|`CodecID/Hint`|A hint/popular name for this codec|
|`CodecID/Url`|A link to more details about this codec ID|
|`CodecID_Description`|Manual description given by the container|
|`Duration`|Play time of the stream in ms|
|`Duration/String`|Play time in format: XXx YYy only, YYy omited if zero|
|`Duration/String1`|Play time in format: HHh MMmn SSs MMMms, XX omited if zero|
|`Duration/String2`|Play time in format: XXx YYy only, YYy omited if zero|
|`Duration/String3`|Play time in format: HH:MM:SS.MMM|
|`Duration_Start`|  |
|`Duration_End`|  |
|`FrameRate`|Frames per second|
|`FrameRate/String`|Frames per second (with measurement)|
|`FrameCount`|Number of frames|
|`TimeStamp_FirstFrame`|TimeStamp fixed in the stream (relative) IN MS|
|`TimeStamp_FirstFrame/Stri`|TimeStamp with measurement|
|`TimeStamp_FirstFrame/Stri`|TimeStamp with measurement|
|`TimeStamp_FirstFrame/Stri`|TimeStamp with measurement|
|`TimeStamp_FirstFrame/Stri`|TimeStamp in format: HH:MM:SS.MMM|
|`TimeCode_FirstFrame`|Time code in HH:MM:SS:FF (HH:MM:SS|
|`TimeCode_Settings`|Time code settings|
|`Title`|Name of this menu|
|`Language`|Language (2-letter ISO 639-1 if exists, else 3-letter ISO 639-2, and with optional ISO 3166-1 country separated by a dash if available, e.g. en, en-us, zh-cn)|
|`Language/String`|Language (full)|
|`Language/String1`|Language (full)|
|`Language/String2`|Language (2-letter ISO 639-1 if exists, else empty)|
|`Language/String3`|Language (3-letter ISO 639-2 if exists, else empty)|
|`Language/String4`|Language (2-letter ISO 639-1 if exists with optional ISO 3166-1 country separated by a dash if available, e.g. en, en-us, zh-cn, else empty)|
|`Language_More`|More info about Language (e.g. Director's Comment)|

## Image ##
| **Property** | **Description** |
|:-------------|:----------------|
|`Count`|Count of objects available in this stream|
|`Status`|bit field (0=IsAccepted, 1=IsFilled, 2=IsUpdated, 3=IsFinished)|
|`StreamCount`|Count of streams of that kind available|
|`StreamKind`|Stream type name|
|`StreamKind/String`|Stream type name|
|`StreamKindID`|Number of the stream (base=0)|
|`StreamKindPos`|When multiple streams, number of the stream (base=1)|
|`StreamOrder`|Stream order in the file, whatever is the kind of stream (base=0)|
|`FirstPacketOrder`|Order of the first fully decodable packet met in the file, whatever is the kind of stream (base=0)|
|`Inform`|Last Inform call|
|`ID`|The ID for this stream in this file|
|`ID/String`|The ID for this stream in this file|
|`UniqueID`|The unique ID for this stream, should be copied with stream copy|
|`UniqueID/String`|The unique ID for this stream, should be copied with stream copy|
|`MenuID`|The menu ID for this stream in this file|
|`MenuID/String`|The menu ID for this stream in this file|
|`Title`|Name of the track|
|`Format`|Format used|
|`Format/Info`|Info about Format|
|`Format/Url`|Link|
|`Format_Commercial`|Commercial name used by vendor for theses setings or Format field if there is no difference|
|`Format_Commercial_IfAny`|Commercial name used by vendor for theses setings if there is one|
|`Format_Version`|Version of this format|
|`Format_Profile`|Profile of the Format|
|`Format_Compression`|Compression mode of the Format|
|`Format_Settings`|Settings needed for decoder used|
|`Format_Settings_Wrapping`|Wrapping mode (Frame wrapped or Clip wrapped)|
|`InternetMediaType`|Internet Media Type (aka MIME Type, Content-Type)|
|`CodecID`|Codec ID (found in some containers)|
|`CodecID/String`|Codec ID (found in some containers)|
|`CodecID/Info`|Info about codec ID|
|`CodecID/Hint`|A hint for this codec ID|
|`CodecID/Url`|A link for more details about this codec ID|
|`CodecID_Description`|Manual description given by the container|
|`Codec`|Deprecated, do not use in new projects|
|`Codec/String`|Deprecated, do not use in new projects|
|`Codec/Family`|Deprecated, do not use in new projects|
|`Codec/Info`|Deprecated, do not use in new projects|
|`Codec/Url`|Deprecated, do not use in new projects|
|`Width`|Width (aperture size if present) in pixel|
|`Width/String`|Width (aperture size if present) with measurement (pixel)|
|`Width_Offset`|Offset between original width and displayed width (aperture size) in pixel|
|`Width_Offset/String`|Offset between original width and displayed width (aperture size)  in pixel|
|`Width_Original`|Original (in the raw stream) width in pixel|
|`Width_Original/String`|Original (in the raw stream) width with measurement (pixel)|
|`Height`|Height (aperture size if present) in pixel|
|`Height/String`|Height (aperture size if present) with measurement (pixel)|
|`Height_Offset`|Offset between original height and displayed height (aperture size) in pixel|
|`Height_Offset/String`|Offset between original height and displayed height (aperture size)  in pixel|
|`Height_Original`|Original (in the raw stream) height in pixel|
|`Height_Original/String`|Original (in the raw stream) height with measurement (pixel)|
|`PixelAspectRatio`|Pixel Aspect ratio|
|`PixelAspectRatio/String`|Pixel Aspect ratio|
|`PixelAspectRatio_Original`|Original (in the raw stream) Pixel Aspect ratio|
|`PixelAspectRatio_Original`|Original (in the raw stream) Pixel Aspect ratio|
|`DisplayAspectRatio`|Display Aspect ratio|
|`DisplayAspectRatio/String`|Display Aspect ratio|
|`DisplayAspectRatio_Origin`|Original (in the raw stream) Display Aspect ratio|
|`DisplayAspectRatio_Origin`|Original (in the raw stream) Display Aspect ratio|
|`ColorSpace`|  |
|`ChromaSubsampling`|  |
|`Resolution`|Deprecated, do not use in new projects|
|`Resolution/String`|Deprecated, do not use in new projects|
|`BitDepth`|  |
|`BitDepth/String`|  |
|`Compression_Mode`|Compression mode (Lossy or Lossless)|
|`Compression_Mode/String`|Compression mode (Lossy or Lossless)|
|`Compression_Ratio`|Current stream size divided by uncompressed stream size|
|`StreamSize`|Stream size in bytes|
|`StreamSize/String`|  |
|`StreamSize/String1`|  |
|`StreamSize/String2`|  |
|`StreamSize/String3`|  |
|`StreamSize/String4`|  |
|`StreamSize/String5`|With proportion|
|`StreamSize_Proportion`|Stream size divided by file size|
|`Encoded_Library`|Software used to create the file|
|`Encoded_Library/String`|Software used to create the file|
|`Encoded_Library/Name`|Info from the software|
|`Encoded_Library/Version`|Version of software|
|`Encoded_Library/Date`|Release date of software|
|`Encoded_Library_Settings`|Parameters used by the software|
|`Language`|Language (2-letter ISO 639-1 if exists, else 3-letter ISO 639-2, and with optional ISO 3166-1 country separated by a dash if available, e.g. en, en-us, zh-cn)|
|`Language/String`|Language (full)|
|`Language/String1`|Language (full)|
|`Language/String2`|Language (2-letter ISO 639-1 if exists, else empty)|
|`Language/String3`|Language (3-letter ISO 639-2 if exists, else empty)|
|`Language/String4`|Language (2-letter ISO 639-1 if exists with optional ISO 3166-1 country separated by a dash if available, e.g. en, en-us, zh-cn, else empty)|
|`Language_More`|More info about Language (e.g. Director's Comment)|
|`Default`|Set if that track should be used if no language found matches the user preference.|
|`Default/String`|Set if that track should be used if no language found matches the user preference.|
|`Forced`|Set if that track should be used if no language found matches the user preference.|
|`Forced/String`|Set if that track should be used if no language found matches the user preference.|
|`Summary`|  |
|`Encoded_Date`|The time that the encoding of this item was completed began.|
|`Tagged_Date`|The time that the tags were done for this item.|
|`Encryption`|  |
|`colour_description_presen`|Presence of colour description|
|`colour_primaries`|Chromaticity coordinates of the source primaries|
|`transfer_characteristics`|Opto-electronic transfer characteristic of the source picture|
|`matrix_coefficients`|Matrix coefficients used in deriving luma and chroma signals from the green, blue, and red primaries|
|`colour_description_presen`|Presence of colour description|
|`colour_primaries_Original`|Chromaticity coordinates of the source primaries|
|`transfer_characteristics_`|Opto-electronic transfer characteristic of the source picture|
|`matrix_coefficients_Origi`|Matrix coefficients used in deriving luma and chroma signals from the green, blue, and red primaries|

## Menu ##
| **Property** | **Description** |
|:-------------|:----------------|
|`Count`|Count of objects available in this stream|
|`Status`|bit field (0=IsAccepted, 1=IsFilled, 2=IsUpdated, 3=IsFinished)|
|`StreamCount`|Count of streams of that kind available|
|`StreamKind`|Stream type name|
|`StreamKind/String`|Stream type name|
|`StreamKindID`|Number of the stream (base=0)|
|`StreamKindPos`|When multiple streams, number of the stream (base=1)|
|`StreamOrder`|Stream order in the file, whatever is the kind of stream (base=0)|
|`FirstPacketOrder`|Order of the first fully decodable packet met in the file, whatever is the kind of stream (base=0)|
|`Inform`|Last Inform call|
|`ID`|The ID for this stream in this file|
|`ID/String`|The ID for this stream in this file|
|`UniqueID`|The unique ID for this stream, should be copied with stream copy|
|`UniqueID/String`|The unique ID for this stream, should be copied with stream copy|
|`MenuID`|The menu ID for this stream in this file|
|`MenuID/String`|The menu ID for this stream in this file|
|`Format`|Format used|
|`Format/Info`|Info about Format|
|`Format/Url`|Link|
|`Format_Commercial`|Commercial name used by vendor for theses setings or Format field if there is no difference|
|`Format_Commercial_IfAny`|Commercial name used by vendor for theses setings if there is one|
|`Format_Version`|Version of this format|
|`Format_Profile`|Profile of the Format|
|`Format_Compression`|Compression method used|
|`Format_Settings`|Settings needed for decoder used|
|`CodecID`|Codec ID (found in some containers)|
|`CodecID/String`|Codec ID (found in some containers)|
|`CodecID/Info`|Info about this codec|
|`CodecID/Hint`|A hint/popular name for this codec|
|`CodecID/Url`|A link to more details about this codec ID|
|`CodecID_Description`|Manual description given by the container|
|`Codec`|Deprecated|
|`Codec/String`|Deprecated|
|`Codec/Info`|Deprecated|
|`Codec/Url`|Deprecated|
|`Duration`|Play time of the stream in ms|
|`Duration/String`|Play time in format: `XXx YYy` only, `YYy` omited if zero|
|`Duration/String1`|Play time in format: `HHh MMmn SSs MMMms`, `XX` omited if zero|
|`Duration/String2`|Play time in format: `XXx YYy` only, `YYy` omited if zero|
|`Duration/String3`|Play time in format: `HH:MM:SS.MMM`|
|`Duration_Start`|  |
|`Duration_End`|  |
|`Delay`|Delay fixed in the stream (relative) IN MS|
|`Delay/String`|Delay with measurement|
|`Delay/String1`|Delay with measurement|
|`Delay/String2`|Delay with measurement|
|`Delay/String3`|Delay in format: `HH:MM:SS.MMM`|
|`Delay/String4`|Delay in format: `HH:MM:SS:FF (HH:MM:SS`|
|`Delay_Settings`|Delay settings (in case of timecode for example)|
|`Delay_DropFrame`|Delay drop frame|
|`Delay_Source`|Delay source (Container or Stream or empty)|
|`List_StreamKind`|List of programs available|
|`List_StreamPos`|List of programs available|
|`List`|List of programs available|
|`List/String`|List of programs available|
|`Title`|Name of this menu|
|`Language`|Language (2-letter ISO 639-1 if exists, else 3-letter ISO 639-2, and with optional ISO 3166-1 country separated by a dash if available, e.g. en, en-us, zh-cn)|
|`Language/String`|Language (full)|
|`Language/String1`|Language (full)|
|`Language/String2`|Language (2-letter ISO 639-1 if exists, else empty)|
|`Language/String3`|Language (3-letter ISO 639-2 if exists, else empty)|
|`Language/String4`|Language (2-letter ISO 639-1 if exists with optional ISO 3166-1 country separated by a dash if available, e.g. en, en-us, zh-cn, else empty)|
|`Language_More`|More info about Language (e.g. Director's Comment)|
|`ServiceName`|  |
|`ServiceChannel`|  |
|`Service/Url`|  |
|`ServiceProvider`|  |
|`ServiceProviderr/Url`|  |
|`ServiceType`|  |
|`NetworkName`|  |
|`Original/NetworkName`|  |
|`Countries`|  |
|`TimeZones`|  |
|`LawRating`|Depending on the country it's the format of the rating of a movie (P, R, X in the USA, an age in other countries or a URI defining a logo).|
|`LawRating_Reason`|Reason for the law rating|
|`Chapters_Pos_Begin`|Used by third-party developers to know about the beginning of the chapters list, to be used by Get(Stream\_Menu, x, Pos), where Pos is an Integer between Chapters\_Pos\_Begin and Chapters\_Pos\_End|
|`Chapters_Pos_End`|Used by third-party developers to know about the end of the chapters list (this position excluded)|