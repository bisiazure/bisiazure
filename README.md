- 👋 Hi, I’m @bisiazure
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
bisiazure/bisiazure is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.




CREATE TABLE [DBA].[STG_IP_Flex_STG_OP_Flex_Configuration](
	[ConfigurationID] [INT] IDENTITY(1,1) NOT NULL,
	[Table_Name] [VARCHAR](1000) NULL,
	[Source_Schema_Name] [VARCHAR](1000) NULL,
	[Source_SQL] [VARCHAR](8000) NULL,
	[Source_Update_Type] [CHAR](1) NULL,
	[Merge_WhereClause] [VARCHAR](MAX) NULL,
	[PreProcessing_SQL] [VARCHAR](MAX) NULL,
	[PostProcessing_SQL] [VARCHAR](MAX) NULL,
PRIMARY KEY CLUSTERED 
(
	[ConfigurationID] ASC
)WITH (PAD_INDEX = OFF, STATISTICS_NORECOMPUTE = OFF, IGNORE_DUP_KEY = OFF, ALLOW_ROW_LOCKS = ON, ALLOW_PAGE_LOCKS = ON) ON [PRIMARY]
) ON [PRIMARY] TEXTIMAGE_ON [PRIMARY]
GO

--->
