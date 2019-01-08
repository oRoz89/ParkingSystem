
                //        CREATE TABLE[dbo].[PARKINGS]
                //        (
 
                //     [ID][int] IDENTITY(1,1) NOT NULL,

                //    [CustomerSlug] [nvarchar] (255) NULL,
                //	[Operater] [int] NULL,
                //	[EnterTime] [datetime] NULL,
                //	[ExitTime] [datetime] NULL,
                //	[Price] [decimal](18, 5) NULL,
                // CONSTRAINT[PK_PARKINGS] PRIMARY KEY CLUSTERED
                //(
                //   [ID] ASC
                //)WITH(PAD_INDEX = OFF, STATISTICS_NORECOMPUTE = OFF, IGNORE_DUP_KEY = OFF, ALLOW_ROW_LOCKS = ON, ALLOW_PAGE_LOCKS = ON) ON[PRIMARY]
                //) ON[PRIMARY]
                //GO




SET IDENTITY_INSERT [dbo].[PARKINGS] ON 

INSERT [dbo].[PARKINGS] ([ID], [CustomerSlug], [Operater], [EnterTime], [ExitTime], [Price]) VALUES (1, N'zeljko-oroz-2', 1, CAST(N'2018-12-20T11:30:00.000' AS DateTime), CAST(N'2018-12-20T12:00:00.000' AS DateTime), CAST(1.00000 AS Decimal(18, 5)))
INSERT [dbo].[PARKINGS] ([ID], [CustomerSlug], [Operater], [EnterTime], [ExitTime], [Price]) VALUES (2, N'zeljko-oroz', 1, CAST(N'2018-12-20T13:00:00.000' AS DateTime), CAST(N'2018-12-20T15:05:00.000' AS DateTime), CAST(3.00000 AS Decimal(18, 5)))
INSERT [dbo].[PARKINGS] ([ID], [CustomerSlug], [Operater], [EnterTime], [ExitTime], [Price]) VALUES (6, N'zeljko-oroz', 4, CAST(N'2018-12-31T08:07:10.000' AS DateTime), CAST(N'2018-12-31T13:46:56.000' AS DateTime), CAST(8.50000 AS Decimal(18, 5)))
INSERT [dbo].[PARKINGS] ([ID], [CustomerSlug], [Operater], [EnterTime], [ExitTime], [Price]) VALUES (7, N'zeljko-oroz-3', 1, CAST(N'2018-12-31T12:08:51.000' AS DateTime), CAST(N'2018-12-31T12:40:15.000' AS DateTime), CAST(1.00000 AS Decimal(18, 5)))
INSERT [dbo].[PARKINGS] ([ID], [CustomerSlug], [Operater], [EnterTime], [ExitTime], [Price]) VALUES (8, N'name_surname', 1, CAST(N'2019-01-03T14:44:37.000' AS DateTime), CAST(N'2019-01-04T08:31:27.000' AS DateTime), CAST(26.50000 AS Decimal(18, 5)))
INSERT [dbo].[PARKINGS] ([ID], [CustomerSlug], [Operater], [EnterTime], [ExitTime], [Price]) VALUES (9, N'test', 1, CAST(N'2019-01-03T14:46:30.000' AS DateTime), CAST(N'2019-01-04T08:41:32.000' AS DateTime), CAST(26.50000 AS Decimal(18, 5)))
INSERT [dbo].[PARKINGS] ([ID], [CustomerSlug], [Operater], [EnterTime], [ExitTime], [Price]) VALUES (10, N'testing', 1, CAST(N'2019-01-03T14:47:42.000' AS DateTime), NULL, NULL)
INSERT [dbo].[PARKINGS] ([ID], [CustomerSlug], [Operater], [EnterTime], [ExitTime], [Price]) VALUES (11, N'testtt', 1, CAST(N'2019-01-03T14:48:49.000' AS DateTime), NULL, NULL)
INSERT [dbo].[PARKINGS] ([ID], [CustomerSlug], [Operater], [EnterTime], [ExitTime], [Price]) VALUES (12, N'test5', 1, CAST(N'2019-01-03T14:49:06.000' AS DateTime), CAST(N'2019-01-04T08:27:53.000' AS DateTime), CAST(26.50000 AS Decimal(18, 5)))
INSERT [dbo].[PARKINGS] ([ID], [CustomerSlug], [Operater], [EnterTime], [ExitTime], [Price]) VALUES (13, N'test6', 1, CAST(N'2019-01-03T14:49:39.000' AS DateTime), NULL, NULL)
INSERT [dbo].[PARKINGS] ([ID], [CustomerSlug], [Operater], [EnterTime], [ExitTime], [Price]) VALUES (14, N'test_7', 1, CAST(N'2019-01-03T14:50:10.000' AS DateTime), NULL, NULL)
INSERT [dbo].[PARKINGS] ([ID], [CustomerSlug], [Operater], [EnterTime], [ExitTime], [Price]) VALUES (15, N'zeljko_oroz_2', 1, CAST(N'2019-01-04T08:13:44.000' AS DateTime), NULL, NULL)
SET IDENTITY_INSERT [dbo].[PARKINGS] OFF
