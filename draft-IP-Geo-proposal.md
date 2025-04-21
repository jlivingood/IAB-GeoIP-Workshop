# IAB Workshop on IP Geolocation (IP-Geo)

# Introduction

This workshop aims to understand the current use cases for publishing and consuming IP address geolocation data. It will explore current methods for publishing this type of data, as well as how the data feeds are discovered and used. It will identify any gaps or other issues, such as uniform methods for discovering an IP-geo data feed, how it can be validated to establish trust and authority, how it can balance end user privacy and localization, and how current practices might be improved. 

The IAB is looking for short position papers on the following topics; however, this list is non-exhaustive and should be interpreted broadly:
* RFC 8805 [1] Discussion: Who is using this RFC, either as a publisher or consumer? What works well or could be improved in this specification?
* Streaming Video Technology Alliance (SVTA) IP Geolocation Specification Discussion: Who is using this specification, either as a publisher or consumer? What works well or could be improved in this specification? Why didn't users of this specification leverage RFC 8805?
* Other Formats: Are there other specifications or widely used practices for publishing and consuming this data that should be explored?
* Discovery Discussion: Are feeds easily discovered today? Should there be a uniform discovery method, such as a well-known URI scheme or some standard mechanism for publishing & discovering feeds?
* Error Reporting: When errors are discovered, how are these reported back to publishers?
* Trust Discussion: How can a consumer of an ip-geo data feed trust that a publisher is authoritative for a given block of IP addresses? Is there a method to use RPKI signing extensions or some other method that would be appropriate?
* Privacy Discussion: How geographically precise does an ip-geo data file need to be in order to balance the need for localization against the ability to identify specific end users?
* IPv6 vs IPv4 Discussion: Should any new standard focus only on IPv6, or should it be extended to IPv4? Why or why not?

## In-Scope Topics
The following topics are considered in-scope; however, this list is non-exhaustive:

Actionable requirements for IP address geolocation, including:
* Formatting of IP-geo files
* Frequency of updating IP-geo data
* Methods of publishing or distributing IP-geo data
* Methods of discoveing, validating, and consuming IP-geo data
* Reporting errors to publishers
* Trust establishment
* Privacy protection
* IPv6 and IPv4 

## Out of scope topics

* Issues not related to the technical aspects of publishing and consuming IP address geolocation data, particularly related to local laws on data privacy or data protection.

# Expected Output

* Workshop report
* Depending upon the discussion, the start of a new specification for IP Address Geolocation

# Pre-Workshop Information Gathering & Outreach

The most interested parties are likely to be Internet Service Providers (ISPs), as well as operators of Virtual Private Networks and Privacy Proxy Networks (e.g., using MASQUE). These parties are publishers of IP Address Geolocation data. Also interested will be content destinations that wish to perform content localization, particularly video streaming providers (given video streaming is tha majority of peak-hour volume on the internet) and Content Delivery Networks (CDNs). Finally there are a number of major IP geolocation value added providers that collect and aggregate this data today, in order to serve content destination provider needs. There are of course many other current users of this data; these examples are not intended to be exclusive. 

Outreach should thus be to member of Regional Internet Registries (RIRs), which assign IP addresses to the aforementioned providers, as well as to the many Network Operator Groups (NOGs) around the world. In addition, outreach to major video streamers can be achieved via the SVTA and similar industry groups. 

The mailing list ip-geo-workshop@iab.org will be used for general announcements and related discussions before (and after) the workshop.

# Workshop

REPLACE/UPDATE THIS TEXT 

Interested participants in the workshop are invited to submit position papers on the workshop topics. There are no restrictions on the format. Participants can choose their preferred format, including Internet-Drafts, text- or word-based documents, or papers formatted similarly to academic publication venues. Submission as PDF is preferred. Paper size is not limited, but brevity is encouraged. Interested participants who have published relevant academic papers may submit these as a position paper, optionally with a short abstract explaining their interest and the paper’s relevance to the workshop. The workshop itself will be focused on discussions based on the position paper topics received.

All inputs submitted and considered relevant will be published on the workshop website. The organizers will issue invitations based on the submissions received. Sessions will be organized according to content, and not every accepted submission or invited attendee will have an opportunity to present; the intent is to foster an active discussion and not simply to have a sequence of presentations. The workshop may also include breakout sessions. A workshop report covering all submissions and discussions will be published afterward.

The workshop will be by invitation only. Those wishing to attend should submit a "position paper" or "expressions of interest" to address the above topics and questions. Position papers from those not planning to participate in the workshop themselves are also encouraged.

Additionally, we request network operators to complete the survey to help us better understand current network management practices, challenges, and future needs. The survey responses will provide valuable input for the workshop - https://ietf.iad1.qualtrics.com/jfe/form/SV_9vQxBRiZqDntarc .

The online workshop would likely be three 2-3h sessions spread over the week based on submissions and the availability of the invited participants.

## Logistics This workshop will be held online.

Initial submissions due: 2024-11-17 EOD (Earlier submissions are appreciated)
Survey responses due: 2024-11-17 EOD
Invitations Issued by: 2024-11-27 EOD
Workshop Dates : TBD -- Maybe June, July, or Sept
Workshop Times: 15:00-18:00 UTC (TBD)
Program Committee: TBD
Feel free to contact the Program Committee with any further questions: XXXX.


# Mailing List Info

Name   		IAB Workshop on IP Address Geolocation (IP-Geo)
Acronym		ip-geo

Personnel (Co-Chairs & Program Committee)
Jana Iyengar
Warren Kumari
Jason Livingood
Tommy Pauly

Group Description

This workshop aims to understand the current use cases for publishing and consuming IP address geolocation data. It will explore current methods for publishing this type of data, as well as how the data feeds are discovered and used. It will identify any gaps or other issues, such as uniform methods for discovering an IP-geo data feed, how it can be validated to establish trust and authority, how it can balance end user privacy and localization, and how current practices might be improved. 

The IAB is looking for short position papers on the following topics; however, this list is non-exhaustive and should be interpreted broadly:
* RFC 8805 [1] Discussion: Who is using this RFC, either as a publisher or consumer? What works well or could be improved in this specification?
* Streaming Video Technology Alliance (SVTA) IP Geolocation Specification Discussion: Who is using this specification, either as a publisher or consumer? What works well or could be improved in this specification? Why didn't users of this specification leverage RFC 8805?
* Other Formats: Are there other specifications or widely used practices for publishing and consuming this data that should be explored?
* Discovery Discussion: Are feeds easily discovered today? Should there be a uniform discovery method, such as a well-known URI scheme or some standard mechanism for publishing & discovering feeds? 
* Trust Discussion: How can a consumer of an ip-geo data feed trust that a publisher is authoritative for a given block of IP addresses? Is there a method to use RPKI signing extensions or some other method that would be appropriate?
* Privacy Discussion: How geographically precise does an ip-geo data file need to be in order to balance the need for localization against the ability to identify specific end users?
* IPv6 vs IPv4 Discussion: Should any new standard focus only on IPv6, or should it be extended to IPv4? Why or why not?


All inputs submitted and considered relevant will be published on the workshop website. The organizers will issue invitations based on the submissions received. Sessions will be organized according to content, and not every accepted submission or invited attendee will have an opportunity to present; the intent is to foster an active discussion and not simply to have a sequence of presentations. A workshop report covering all submissions and the workshop discussion will be published afterwards.

The workshop will be by invitation only. Those wishing to attend should submit a 1 - 3 page position paper to address the above topics and questions. Position papers from those not planning to attend the workshop themselves are also encouraged.

Please indicate your interest by submitting a research proposal by June 1, 2025 to ip-geo-workshop-pc@iab.org

The Program Committee members are Jana Iyengar (IAB, Fastly), Warren Kumari (IAB, Google), Jason Livingood (IAB, Comcast), Tommy Pauly (IAB, Apple).

Feel free to contact the program committee with any further questions: ip-geo-workshop-pc@iab.org.

This workshop will be held online during the week of XXXX, likely supporting three 2-3 hour sessions spread over the week based on submissions and the availability of the invited participants.

[1] https://www.rfc-editor.org/rfc/rfc8805.html
[2] https://github.com/intarchboard/responsibilities/issues/26#:~:text=for%20streaming%20video-,SVTA5010%2DGeo%2DData%2DFor%2DIPV6_v1%2D2_08212023%2D9biq1v.pdf,-.%20One%20example%20of

